A professional, dynamic, and mobile-responsive statistics engine built for the **Maine East Cricket Club**. This dashboard fetches live match data from Google Sheets and transforms it into an interactive experience featuring player profiles, head-to-head comparisons, and performance analytics.

---

## 🚀 Live Demo
**[View the Dashboard Live](https://zx-dr4gon7.github.io/mecricket/)** *(Note: Replace 'reponame' with your actual repository name in your GitHub settings)*

---

## ✨ Key Features

### 📊 Interactive Dashboard
* **Real-time Data:** Fetches the latest stats directly from Google Sheets via CSV export.
* **Visual Analytics:** Dynamic charts powered by **Chart.js** showing club trends and leaderboards.
* **Smart Tables:** Sortable batting and bowling tables built with **Bulma CSS**.

### 👤 Advanced Player Profiles
* **Dynamic Sports Cards:** Clicking any player opens a dedicated profile view.
* **Hero Stats:** Instant visibility of key metrics (Runs, Wickets, Average, S/R).
* **Automatic Highlighting:** Elite performances are automatically tagged with a 🔥 and highlighted in green.

### ⚔️ VS Mode (Comparison Tool)
* **Head-to-Head:** Select any two players to see their stats side-by-side.
* **Smart Comparison:** The engine automatically highlights the "winner" of each stat category (e.g., lower Economy wins, higher Strike Rate wins).

### 🌗 Theme Engine
* **Dark/Light Mode:** A fluid, aesthetic toggle switch in the header allows users to choose their preferred viewing experience.
* **Persistent Settings:** Your theme choice is saved to your browser so it stays consistent on your next visit.

---

## 🛠️ Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **HTML5/JS** | Core logic and DOM manipulation |
| **Bulma CSS** | Modern, responsive UI framework |
| **Chart.js** | Data visualization and trending |
| **Google Sheets** | Cloud-based backend database |
| **GitHub Pages** | Fast, reliable web hosting |

---

## ⚙️ How it Works

The dashboard functions as a **Single Page Application (SPA)**:
1. **Fetch:** On load, the JavaScript `fetch()` API calls the Google Sheets CSV endpoints.
2. **Clean:** The data is parsed, skipping metadata rows and empty columns to ensure accuracy.
3. **Render:** The engine builds the tables and charts dynamically.
4. **Interact:** All transitions (Profile -> VS Mode -> Dashboard) happen instantly without page reloads using CSS fade animations.

---

## 🤝 Contributing
This dashboard is maintained for the **Maine East Cricket Club**. If you have suggestions for new stats or features:
1. Open an **Issue** in this repository.
2. Submit a **Pull Request** with your proposed changes.

---

## 📜 License
This project is open-source and available under the **MIT License**.

---
*Created with ❤️ for the Maine East Cricket Community.*
"""

# Write the content to a file
with open("README.md", "w", encoding="utf-8") as f:
    f.write(readme_content)

print("README.md has been generated.")
