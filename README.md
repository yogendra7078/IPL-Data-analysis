# IPL Data Analysis using Apache Spark and PySpark

## 📌 Overview

This project performs end-to-end exploratory data analysis (EDA) on Indian Premier League (IPL) cricket datasets using **Apache Spark** and **PySpark**. The goal is to extract meaningful insights, visualize trends, and showcase storytelling using data.

> 🔍 The analysis includes data cleaning, feature engineering, statistical summarization, and interactive data visualization.

---

## 📂 Dataset

- **Source:** Kaggle IPL Dataset
- **Files Used:**
  - `matches.csv`
  - `deliveries.csv`

---

## 🛠️ Technologies Used

- Python
- PySpark (Apache Spark)
- Pandas (for preprocessing)
- Plotly (interactive charts)
- Matplotlib & Seaborn (static visualizations)
- Streamlit (interactive dashboard - optional for expansion)

---

## 📈 Key Visualizations and Insights

### 1. 🔝 Most Winning Teams (Bar Chart)
- Bar graph showing total matches won by each team.
- ✅ **Insight:** Mumbai Indians dominate the IPL with the highest number of wins.

### 2. 📌 Toss vs Match Wins (Bar Chart)
- Shows correlation between toss win and match win.
- ✅ **Insight:** Toss advantage exists but is not a dominant factor.

### 3. 💪 Top Run Scorers (Horizontal Bar Chart)
- Batsmen with the highest cumulative runs across seasons.
- ✅ **Insight:** Virat Kohli leads with exceptional consistency.

### 4. 🎯 Best Bowlers (Bar Chart + Box Plot)
- Visualized using total wickets and economy rate.
- ✅ **Insight:** Bhuvneshwar Kumar and Lasith Malinga are standout performers.

### 5. 📍 Matches by City (Pie Chart)
- Pie chart shows distribution of IPL matches across cities.
- ✅ **Insight:** Mumbai and Bengaluru host the most games.

---

## 🌟 Data Storytelling

The visualizations go beyond numbers by drawing narratives:
- **Consistency** of teams like MI & CSK in both tosses and matches.
- **Geographical dominance** shows which cities are IPL hubs.
- **Individual legends** are identified through cumulative and per-match stats.

Annotations, color highlights, and chart labels enhance the interpretability of each plot.

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/IPL-Data-analysis.git
   cd IPL-Data-analysis
