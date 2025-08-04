
# 🛒 Retail Sales Analysis Dashboard | Power BI

An interactive Power BI dashboard that explores retail sales performance across products and regions. This project demonstrates data cleaning, transformation, modeling, and insightful visualization, helping convert raw data into business decisions.

---

## 📄 Project Description

This Power BI project delivers a detailed analysis of retail sales data, covering key metrics such as revenue, profit, product performance, and regional sales distribution. The dataset is initially raw and "dirty," requiring cleaning and transformation before meaningful analysis can be performed.

---

## 📊 Dashboard Preview

![Retail Sales Dashboard Preview](./Dashboard.PNG)

> 📌 Use slicers to filter by date, region, and product. Analyze KPIs, trends, and profit across multiple dimensions.

---

## 🧩 Features & KPIs Tracked

- 💰 **Total Revenue** and **Sum of Profit**
- 💹 **Average Profit Margin**
- 📦 **Average Revenue per Order**
- 📊 **Revenue Trends over Time**
- 🎯 **Top Products by Revenue and Profit**
- 🌍 **Regional Sales & Profitability**
- ⚙️ **Cost vs Price Analysis by Product**
- 📈 **Interactive Filters (Date, Region, Product)**

---

## 🗂️ Project Structure

```
retail-sales-analysis/
│
├── retail sales analysis.pbix             # Power BI Dashboard file
├── Dashboard.PNG                          # Screenshot of the final dashboard
├── README.md                              # Project documentation
└── data/
    └── retail_sales_data_dirty.csv        # Raw retail sales dataset
```

---

## 📝 Data Source

- **File:** `retail_sales_data_dirty.csv`
- **Format:** CSV
- **Columns:**
  - `Order Date`, `Product`, `Category`, `Region`, `Sales`, `Cost`, `Profit`, `Units Sold`, `Profit Margin`, etc.
- **Notes:**
  - The dataset includes inconsistencies, nulls, and duplicates that were cleaned using Power Query.
  - Date fields were parsed, numerical fields were transformed, and calculated columns were created for KPI analysis.

---

## ⚙️ Tools & Technologies Used

- **Power BI Desktop** – For data modeling and visualization  
- **Power Query** – Data cleaning and preparation  
- **DAX (Data Analysis Expressions)** – Measures and calculated columns  
- **CSV** – Data source format

---

## 🚀 How to Use This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/retail-sales-analysis.git
   ```

2. Open the `.pbix` file with Power BI Desktop.

3. Ensure the dataset is correctly connected:
   - Go to **Home > Transform Data > Data Source Settings**
   - Relink to: `./data/retail_sales_data_dirty.csv` if needed.

4. Interact with the dashboard by using:
   - Date range slider
   - Product and region slicers
   - Hover and click-to-filter on visuals

---

## 📚 Key Insights

- 🟢 **North America** has the highest total profit and revenue.
- 💸 **Tablet** sales drive the highest revenue.
- 📊 Sales spike during specific time windows, showing clear seasonality.
- 📉 Products like **Smartphones** show lower profit margins despite moderate revenue.
- 🧮 Average revenue per order is ₹4.95K, with a profit margin of 25%.

---

## 📌 Future Improvements

- Enable predictive forecasting using built-in analytics or Python/R in Power BI
- Automate data refresh from a cloud data source
- Add drill-through pages for detailed product or region-level analysis
- Publish dashboard to Power BI service and embed online

---

## 🙌 Acknowledgments

- Data cleaned and modeled using Power Query and DAX
- Project developed for educational and portfolio purposes

---

## 📧 Contact

**Your Name**  
📫 [your.email@example.com](mailto:your.email@example.com)  
🔗 [LinkedIn](https://linkedin.com/in/yourusername)  
🌐 [Portfolio](https://yourportfolio.com)

---

> ⭐ *Feel free to fork this project, suggest improvements, or raise an issue. Feedback is welcome!*
