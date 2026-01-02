# Retail Analytics Dashboard (Power BI)

## Project Overview

This project is an **end-to-end retail data analytics solution** built using **SQL, Python (Pandas), and Power BI**. The goal is to analyze **sales performance, inventory movement, and vendor efficiency** and present insights through an interactive, multi-page Power BI dashboard.

The project simulates a **real-world retail business scenario**, focusing on data validation, reconciliation, and business-driven insights.

---

## Data Sources

The analysis is built using **six relational tables** stored in a database:

1. **Purchases** – Purchase transactions by vendor and product
2. **Purchase Prices** – Standard pricing reference data
3. **Beginning Inventory** – Opening stock levels
4. **Ending Inventory** – Closing stock levels
5. **Vendor Invoice** – Invoice and approval details
6. **Sales** – Sales transactions with tax and volume

Data was queried using **SQL**, processed and aggregated using **Python (Pandas)**, and visualized in **Power BI**.

---

## Tools & Technologies

* **SQL** – Data extraction and joins
* **Python (Pandas, NumPy)** – Data cleaning, aggregation, and validation
* **Power BI** – Data modeling, DAX, and dashboard design

---

## Key Analysis Performed

* Sales vs Purchase comparison at store and brand level
* Gross profit and profit margin analysis
* Inventory movement and accuracy validation
* Vendor performance evaluation using approval rates and freight costs
* Invoice vs purchase reconciliation at PO and vendor level

Real-world data issues such as **vendor mismatches across systems** were identified and documented as part of the analysis.

---

## Dashboard Pages

### Executive Overview

* KPI cards for Sales, Purchases, Profit, and Margin
* Sales vs Purchases by Store
* Gross Profit by Store

### Inventory Analysis

* Inventory Waterfall (Beginning → Ending)
* Inventory Accuracy comparison
* Shrinkage validation

### Sales Performance Analysis

* Sales vs Quantity scatter plot
* Sales vs Profit analysis
* Top 10 Brands by Sales
* Bottom-performing products table

### Vendor Performance Dashboard

* Top Vendors by Purchase Amount
* Purchase vs Invoice Amount comparison
* Vendor Approval Rate analysis
* Freight Cost vs Purchase Amount
* Vendor Performance Details table

---

## Vendor Summary Table

The final vendor-level dataset includes:

* Total Purchase Quantity & Amount
* Average Purchase Price
* Total Invoice Quantity & Amount
* Freight Cost
* Invoice Approval Rate

This table was created using **Pandas aggregations and joins**, ensuring no data loss at PO level.

---

## Data Validation & Quality Checks

* Source totals validated against aggregated totals
* PO-level reconciliation verified
* Merge key uniqueness checks performed
* Vendor mismatches documented as business insights

These steps ensure the dashboard reflects **accurate and trustworthy data**.

---

## Key Business Insights

* Identification of top-performing and high-risk vendors
* Stores with strong sales but low profitability
* Products contributing to low margins
* Vendors with high freight cost inefficiencies

---

## Files Included
The Power BI (.pbix) file is available upon request.
* Power BI Dashboard (.pbix)
* Python notebooks / scripts
* SQL queries

---

## Future Enhancements

* Drill-through pages for store-level analysis
* Automated data refresh pipeline
* Predictive inventory forecasting

---

## Dashboard Screenshots
Page 1 – Executive Overview
<img width="1330" height="745" alt="image" src="https://github.com/user-attachments/assets/2a00b1a4-e0ea-4649-8339-defa810445ac" />

Page 2 – Inventory Analysis
<img width="1335" height="743" alt="image" src="https://github.com/user-attachments/assets/4985c827-b7e2-4293-9feb-01869201b2a5" />

Page 3 – Sales Performance
<img width="1339" height="740" alt="image" src="https://github.com/user-attachments/assets/69f9591a-217a-4069-a059-5210e6df9fbb" />

Page 4 – Vendor Analysis
<img width="1327" height="735" alt="image" src="https://github.com/user-attachments/assets/a489edcb-1870-4c30-be51-86c7d7a5463b" />



## Author

**Kajal Yadav**
Data Analyst | SQL | Python | Power BI

