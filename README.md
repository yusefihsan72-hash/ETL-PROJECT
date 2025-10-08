# ETL-PROJECT
Project Using SQL and CSV Files

Project Description:
This project focuses on building a small-scale ETL (Extract, Transform, Load) pipeline using SQL and CSV files. The main goal is to read raw CSV data, clean and transform it, and then load it into a structured SQL database for analysis and reporting.

Project Requirements

Data Source:

One or more CSV files containing raw data (e.g., sales, employees, products, or transactions).

Extraction Phase:

Read and import the CSV files into a staging area or temporary SQL table.

Verify file integrity (check headers, encoding, and missing columns).

Transformation Phase:

Clean data by removing duplicates and null values.

Standardize date and numeric formats.

Create new calculated columns (e.g., total sales = quantity × price).

Apply validation checks (e.g., no negative quantities or prices).

Loading Phase:

Load the cleaned and transformed data into the final SQL tables.

Use SQL scripts to automate insert and update operations.

Deliverables:

SQL scripts for each ETL step (Extract, Transform, Load).

Final SQL database schema.

Sample queries for reporting (e.g., total sales per region, top 5 products).

Tools Used

SQL (MySQL / PostgreSQL / SQLite)

CSV files

Expected Outcome

A clean, structured database ready for reporting and analysis, improving data quality and making it easier to generate insights using SQL queries.
