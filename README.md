# Climate Change Dashboard Project

### By: Yugank Singh | yugank942@gmail.com

---

## Project Overview

This project analyzes over 60 years of global climate data to visualize the relationship between CO₂ emissions, economic factors, and rising global temperatures. The goal was to develop two interactive dashboards—one in Excel and one in Power BI—to explore these trends.

---

## Final Deliverables

You can find all the final files in this repository.

* **Summary Presentation:** [`Yugank Singh - Climate Change Analysis.pptx`](./PROJECT%20REPORT/Climate%20Change.pptx)
* **Summary PDF:** [`Yugank Singh - Climate Change Analysis.pdf`](./PROJECT%20REPORT/Climate%20Change.pdf)
* **Power BI Dashboard:** [`ClimateChangeDashboard.pbix`](./POWER%20BI%20DASHBOARD%20FILE/ClimateChangeDashboard.pbix)
    * *Requires Microsoft Power BI Desktop to view.*
* **Excel Dashboard:** [`YUGANK SINGH - Excel Climate Dashboard.xlsx`](./EXCEL%20DASHBOARD/YUGANK%20SINGH-%20Excel%20Climate%20Dashboard.xlsx)
    * *Requires the Microsoft Excel desktop app for full interactivity (slicers). The web preview will not work correctly.*

---

## 1. Data Cleaning & Transformation (ETL)

The raw dataset was cleaned and prepared in Power BI's Power Query using the following steps:
- **Filtered** data to the 1960-2022 period.
- **Selected** 7 key columns for analysis (country, year, GDP, population, CO₂, temp. change).
- **Removed** null values from core analytical columns.
- **Corrected** data types, especially for the `temperature_change_from_ghg` column which was initially misinterpreted.

---

## 2. Key Insights from the Power BI Dashboard

* **Strong Correlation:** The dashboard clearly shows a strong positive correlation between the rise in global CO₂ emissions and the increase in average global temperature.
* **Economic Drivers:** Scatter plots reveal that higher GDP and population are generally associated with higher CO₂ emissions.
* **DAX Measures:** Key metrics like `Total CO2` and `Average Temperature` were created using DAX to enable dynamic and accurate filtering across the entire report.

---

## 3. Challenges & Solutions

* **Data Structure:** The dataset included a pre-aggregated "World" value alongside individual countries. To avoid misleading visuals, the primary analysis was focused on this global trend, while still allowing for individual country exploration via slicers.
* **Tooling:** Sharing an interactive Power BI report without a Pro license was a challenge. This GitHub repository provides direct access to the `.pbix` file for anyone with Power BI Desktop, ensuring the full interactive experience can be reviewed.

---