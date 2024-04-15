# Home_Sales
Module 22 Challenge

## Solution
There is a Folder called "Starter_code" and there is a file called home_sales.ipynb with code. 

### Instructions
Rename the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.
Import the necessary PySpark SQL functions for this assignment.
Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.
Create a temporary table called home_sales.

# Answer these questions using SparkSQL:

*  What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
![output](4bedroom_img2.png)

*  What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
![output](2.png)

*  What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
![output](3bedroom_img3.png)

    What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
![output](averagepric_3beds_3bath_2ksqft_img4.png)

Cache your temporary table home_sales.
Check if your temporary table is cached.
Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
![output](avgprice_timetoreport_img5.png)

Partition by the "date_built" field on the formatted parquet home sales data.
Create a temporary table for the parquet data.

Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

![output](avgprice_timetoreportuncached_img5.png)

Uncache the home_sales temporary table.
Verify that the home_sales temporary table is uncached using PySpark.
Download your Home_Sales.ipynb file and upload it into your "Home_Sales" GitHub repository.
