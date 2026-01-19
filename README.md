
# 📊 Retail Sales SQL Case Study (Coding Ninjas)

## 📌 Project Overview

This project analyzes a retail sales dataset to uncover insights related to **customer behavior, product performance, inventory status, and sales trends** using SQL (MySQL).

The objective is to simulate a real-world business scenario where SQL is used not just to retrieve data, but to **support decision-making**.

---

## 🗂️ Dataset Description

The analysis is based on three main tables:

### 1️⃣ Customer_Profile

* `CustomerID`
* `Age`
* `Gender`
* `Location`
* `Join_Date`

### 2️⃣ Sales_Transaction

* `TransactionID`
* `CustomerID`
* `ProductID`
* `QuantityPurchased`
* `Price`
* `TransactionDate`

### 3️⃣ Product_Inventory

* `ProductID`
* `ProductName`
* `Category`
* `StockLevel`
* `Price`

---

## 🎯 Business Objectives

* Understand **customer purchasing behavior**
* Identify **high-performing and underperforming products & categories**
* Analyze **sales trends over time**
* Evaluate **inventory distribution vs sales**
* Segment customers based on **value and activity**
* Identify **inactive customers**

---

## ❓ Key Business Questions Solved

### Product & Category Analysis

1. Top 5 and Bottom 5 products by quantity sold
2. Top 5 categories by quantity sold
3. Top 5 categories by total transaction amount
4. Category with the highest and lowest stock levels and their sales impact

### Customer Analytics

5. Customer segmentation based on:

   * total quantity purchased
   * total transaction amount
6. Top customers by:

   * total transaction value
   * average order value
7. Inactive customers (customers with no purchase history)

### Time-Based Analysis

8. Quarterly sales trend
9. Month-over-Month (MoM) sales growth
10. Monthly number of transactions

### Demographic Analysis

11. Gender and age-group based sales analysis

---

## 🛠️ Tools & Technologies Used

* **SQL (MySQL)**
* MySQL Workbench
* Window Functions
* CTEs (WITH clauses)
* Aggregations & Joins
* Date & Time Functions

---

## 🧠 Key Insights

* A small segment of customers contributes a **disproportionately high share of total revenue**.
* Some categories show **high sales volume but low stock**, indicating potential stock-out risks.
* Clear **seasonality and monthly fluctuations** are observed in transaction volume.
* Certain product categories perform well in quantity but not in transaction value, highlighting **pricing differences**.
* A group of registered customers has **never made a purchase**, indicating an opportunity for targeted marketing.

---

## ⚠️ Assumptions & Limitations

* Sales is defined as **number of products purchased**, not revenue, unless explicitly stated.
* Customer churn could not be calculated accurately due to the absence of:

  * cancellation dates
  * inactivity duration rules
    Instead, **inactive customers** were identified.
* No discount, promotion, or return data was available.

---

## 📂 Repository Structure

```
Retail-SQL-Case-Study/
│
├── Queries/
│   ├── Product_Analysis.sql
│   ├── Customer_Segmentation.sql
│   ├── Sales_Trends.sql
│   ├── Inventory_Analysis.sql
│
├── README.md
└── Dataset_Schema.png
```

---

## 📈 Learning Outcomes

* Translated business objectives into analytical SQL queries
* Strengthened understanding of **window functions & time-based analysis**
* Learned to handle **ambiguous business metrics** (churn vs inactivity)
* Improved SQL structuring and readability for real-world use cases

---

## 🚀 How to Run

1. Import datasets into MySQL
2. Execute queries from the `Queries/` folder
3. Analyze outputs for insights

---

## 📬 Contact

**Yash Singh**
Aspiring Data Analyst
Skills: SQL | Power BI | Python | Excel

---


