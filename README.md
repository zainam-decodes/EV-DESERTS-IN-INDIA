# India EV Infrastructure Gap Analysis Dashboard 🇮🇳⚡

A data-driven analytics project evaluating regional disparities, growth timelines, and localized grid strains within India’s electric vehicle ecosystem. This 3-page interactive Tableau dashboard identifies critical bottlenecks blocking sustainable EV transitions across 36 States and Union Territories.

---

## 📊 Data Authenticity & Sources

* **EV Registration Baseline:** Official government **VAHAN Dashboard** ecosystem.
* **Infrastructure Mapping:** Verified public and commercial public charging station registries.

---

## 🔍 Dashboard Architecture & Key Insights

### 1. Overview Layer
* **Components:** National KPI Blocks, India Geographic Density Map, Charger Type Distribution, Top 10 Infrastructure Bottlenecks.
* **Key Takeaway:** India faces a sharp national **EV-to-Charger Ratio of 67.02**. Nearly 70% of public installations rely on slow chargers (76.4k slow vs. 34.3k fast), limiting commercial turnaround times and intensifying range anxiety.

### 2. Deep Insights Layer
* **Components:** Dual-Axis Widening Disparity Timeline, State Adequacy Scatter Plot, CAGR Leaderboard, Segment Strain Matrix.
* **Key Takeaway:** Post-2021, EV registrations scaled exponentially while infrastructure expanded linearly. The **Segment Strain Matrix** reveals that this structural deficit is disproportionately driven by commercial **3-Wheelers (3W)** rather than personal 4W cars.

### 3. Experience Layer
* **Components:** Charging Density Index (CDI) Bar Chart, Vehicle-Specific Simulated Strain Heatmap, Fast Charger Readiness % by State.
* **Key Takeaway:** Mountainous terrains (e.g., Arunachal Pradesh and Sikkim) face severe pressure on the custom CDI scale due to geographical installation complexities. Nationally, even the highest-ranked states cap out near **32% Fast Charger Readiness**.

---

## 🛠️ Technical Architecture

* **BI & Visualization:** Tableau Desktop (Advanced parameters, spatial mapping, custom dual-axis timelines, and condition-mapped color saturation).
* **Data Engineering:** SQL / Excel (Data cleaning, normalizing geographic naming conventions, and modeling the unified CDI metric).

---

## 📂 Repository Structure

```directory
├── data/
│   ├── raw/                  # Source VAHAN and charging registry datasets
│   └── processed/            # Aggregated and modeled data extracts
├── workbook/
│   └── ev_infrastructure_gap_india.twbx   # Packaged Tableau Workbook
└── README.md                 # Project Documentation
