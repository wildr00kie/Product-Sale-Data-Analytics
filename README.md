# 📊 Product Sales & Revenue Analytics | Tableau & Business Intelligence Project

A comprehensive data analytics portfolio project examining 12+ years of multi-product transaction data, revenue trends, pricing realization, transaction distributions, seasonality heatmaps, and portfolio cross-correlations using **Tableau**, **Google Sheets**, and **Google Docs**.

---

## 📌 Executive Summary

This repository presents an end-to-end business intelligence analysis of multi-product transactional sales performance. By evaluating top-line performance, unit volume vs. value relationships, transaction sizing distributions, and demand seasonality, this project offers strategic recommendations for portfolio pricing, marketing synchronization, and revenue optimization.

### Key Business Insights:
* **Macro Stability:** Total combined monthly revenue maintains a resilient foundation between **₹1.4M and ₹1.7M**, with monthly growth velocity bounded predictably between **-18% and +25%**.
* **Core Revenue Driver:** **Product 3** serves as the optimal financial anchor, commanding **₹78.4M in total revenue** on 14.5M units sold due to a balanced mid-tier price point (**₹5.42**).
* **Price Realization Efficiency:** **Product 2** matches Product 1’s ₹60M+ total revenue output on half the unit volume (**9.8M vs. 19M units**) due to its premium unit price (**₹6.34 vs. ₹3.17**).
* **Standard Transaction Sizing:** Transaction values follow a symmetric bell curve centered at **₹54K–₹55K per order**, with core transactions clustering tightly between ₹35K and ₹68K.
* **H2 Seasonality & Portfolio Synergy:** Sales density accelerates significantly in H2 (July–December), with peak windows surpassing **₹3.18M per cell**. Strong positive volume correlation across all products confirms zero portfolio cannibalization.

---

## 📁 Repository & Project Files

| File / Document | Format | Description |
| :--- | :--- | :--- |
| **Product Sale Data Tableau** | `.twb` | Interactive Tableau workbook containing all 8 dashboard views, calculations, and dual-axis charts. |
| **Product Sale Data Records** | `Google Sheets` | Raw transaction dataset, aggregated measures, revenue bins, and unit volume metrics. |
| **Product Sale Data Presentation** | `.pptx` | Fully editable presentation slide deck with high-resolution visual charts. |
| **Product Sale Data Presentation** | `.pdf` | Exported presentation deck for quick viewing and review. |
| **Product Sale Data Notes** | `Google Docs` | Detailed presentation transcript, slide bullet points, and presenter speaker notes. |

---

## 📈 Visualizations & Key Insights

### 1. Monthly Combined Revenue Trend with Moving Average (Dual Axis)
* **Description:** Tracks total revenue over time alongside a moving average curve to evaluate long-term macro trajectory and short-term volatility.
* **Key Insights:**
  * Baseline monthly revenue remains consistently stable between **₹1.4M and ₹1.7M** across a 12-year window.
  * The moving average smooths monthly zig-zag fluctuations, revealing recurring cyclical peaks reaching near **₹1.75M**.
  * Severe drops at the extreme boundaries (start of 2010 and end of 2023) reflect partial logging periods rather than business loss.

---

### 2. Product Revenue Share Over Time (Stacked Area Chart)
* **Description:** Breaks down monthly revenue contributions across individual products (P1–P4) to evaluate product mix stability.
* **Key Insights:**
  * **Product 1** acts as the baseline anchor, consistently generating **40%–50% (₹650K–₹800K/mo)** of total revenue.
  * **Products 2 and 3** form consistent, equal-tier secondary layers contributing ~₹350K–₹400K each per month.
  * Product revenue proportions remain remarkably constant across the entire 12-year timeline with no structural decay.

---

### 3. Period-over-Period Revenue Growth (MoM)
* **Description:** Measures monthly percentage growth rate changes to evaluate growth velocity and standard variance bounds.
* **Key Insights:**
  * Standard month-over-month (MoM) growth fluctuates predictably between **-18% and +25%**.
  * Peak operational surges occurred in early 2020 with MoM growth spiking near **+25%**.
  * Standard negative contractions stay capped strictly above **-18%**, proving strong customer retention.

---

### 4. Product Revenue vs. Volume Breakdown (Side-by-Side Bar Chart)
* **Description:** Compares total financial revenue against total physical unit volume moved per product.
* **Key Insights:**
  * **Product 3** leads total revenue at **₹78,429,590** on 14,470,404 units sold.
  * **Product 1** moves the highest unit volume (**18,960,506 units**), yielding **₹60,104,804**.
  * **Product 2** generates **₹62,127,530** on only 9,799,295 units, demonstrating superior revenue realization per unit.
  * **Product 4** trails in both revenue (**₹36,848,553**) and volume (**5,168,100 units**).

---

### 5. Average Selling Price (ASP) Comparison by Product
* **Description:** Evaluates unit pricing tiers across the portfolio to understand revenue generation efficiency.
* **Key Insights:**
  * **Product 4** commands the highest premium price at **₹7.13/unit**.
  * **Product 2** represents the secondary premium tier at **₹6.34/unit**.
  * **Product 3** operates at a balanced mid-market price point of **₹5.42/unit**.
  * **Product 1** serves as the low-cost volume driver at **₹3.17/unit**, establishing a **125% price spread** across the portfolio.

---

### 6. Transaction Revenue Distribution (Histogram)
* **Description:** Groups 4,600 distinct transactions into revenue bins to identify order sizing patterns and distribution skew.
* **Key Insights:**
  * Follows a normal bell-curve distribution centered around mid-tier order sizes.
  * Peak transaction frequency (mode) occurs at the **54K–55K revenue bin** (270 distinct orders).
  * Core transactions cluster between **35K and 68K**, while micro-orders (<20K) and enterprise orders (>80K) remain rare outliers.

---

### 7. Peak Sales Seasonality Heatmap
* **Description:** Maps cumulative revenue across months and days of the week to pinpoint peak demand operational windows.
* **Key Insights:**
  * Revenue accelerates in the second half of the year (**July–December**), driven by monthly seasonality rather than day-of-week patterns.
  * **February** represents the annual performance floor (dipping to ₹2.32M on Fridays).
  * Peak operational windows occur on **Fridays in July (₹3.18M)**, **Saturdays in October (₹3.18M)**, and **Thursdays in December (₹3.11M)**.

---

### 8. Product Cross-Volume Correlation (Scatter Matrix)
* **Description:** Analyzes pairwise unit volume relationships between products to identify complementary or cannibalistic trends.
* **Key Insights:**
  * All trend lines exhibit **positive linear slopes**, confirming strong complementary demand.
  * Volume surges in primary products (P1 and P3) directly lift sales volume in secondary products (P2 and P4).
  * Zero downward slopes indicate an complete absence of product cannibalization.

---

## 💡 Strategic Recommendations

1. **Capitalize on H2 Seasonality:** Shift promotional spend, inventory provisioning, and logistics resources into Q3/Q4 to capture peak demand windows (July, October, December).
2. **Product 4 Volume Expansion:** Launch targeted marketing campaigns for Product 4. Its high price point (₹7.13) offers significant margin upside if unit volume (5.2M) can be scaled.
3. **Cross-Selling & Product Bundling:** Leverage positive cross-product volume correlations by bundling low-cost entry products (P1) with high-margin offerings (P2 & P4) ahead of peak seasonal cycles.

---

## 🛠️ Tools & Technologies Used
* **Data Visualization:** Tableau Desktop (`.twb`)
* **Data Prep & Calculation:** Google Sheets / MS Excel
* **Documentation & Notes:** Google Docs
* **Presentation Deck:** Microsoft PowerPoint (`.pptx`), PDF
