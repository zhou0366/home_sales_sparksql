# Home Sales SparkSQL

In this challenge, we will be reading a data set of home sales data and use SparkSQL to query the data with SQL queries.

# 1. Read in the AWS S3 bucket into a DataFrame.

Results:

![image](https://github.com/zhou0366/home_sales_sparksql/assets/22827830/d137e6ee-c509-4051-9a82-fff8248f68de)

# 3. What is the average price for a four bedroom house sold per year, rounded to two decimal places?

The resulting averages are shown below:

![image](https://github.com/zhou0366/home_sales_sparksql/assets/22827830/aec2d312-2007-4c72-8c81-1b1251f22437)

# 4. What is the average price of a home for each year the home was built, that have 3 bedrooms and 3 bathrooms, rounded to two decimal places?

The resulting averages are shown below:

![image](https://github.com/zhou0366/home_sales_sparksql/assets/22827830/d05eff46-411e-4362-830b-72a7c59cd7a8)

# 5. What is the average price of a home for each year the home was built, that have 3 bedrooms, 3 bathrooms, with two floors, and are greater than or equal to 2,000 square feet, rounded to two decimal places?

The resulting averages are shown below:

![image](https://github.com/zhou0366/home_sales_sparksql/assets/22827830/50df3b51-4cc1-4931-a197-1f1709003afa)

# 6. What is the average price of a home per "view" rating, rounded to two decimal places, having an average home price greater than or equal to $350,000?

The resulting averages are shown below:

![image](https://github.com/zhou0366/home_sales_sparksql/assets/22827830/2643d950-6b76-44b3-acdf-b6b8f8a6315c)

# 9. Using the cached data, run the last query above, that calculates the average price of a home per "view" rating, rounded to two decimal places, having an average home price greater than or equal to $350,000.

The resulting averages are shown below:

![image](https://github.com/zhou0366/home_sales_sparksql/assets/22827830/0fba561d-acc0-493a-ba07-825184591ca4)

This query ran in 0.5610 seconds while the first ran in 1.8096

# 13. Using the parquet DataFrame, run the last query above, that calculates the average price of a home per "view" rating, rounded to two decimal places, having an average home price greater than or equal to $350,000.

The resulting averages are shown below:

![image](https://github.com/zhou0366/home_sales_sparksql/assets/22827830/549f4719-3771-4efc-a656-22a475b04853)

This query ran in 0.7294 seconds
