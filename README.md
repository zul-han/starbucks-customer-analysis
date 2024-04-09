# Customer Survey Analysis: Coffee Shop Industry
This repository contains an exploratory data analysis (EDA) of coffee shop customer data (Starbucks-Kaggle data), providing valuable insights into customer demographics, behavior, preferences, and satisfaction levels. The analysis aims to uncover patterns and trends that can inform business strategies and drive data-driven decision-making for coffee shop .

## Project Overview
Understanding customer demographics, behaviour and satisfaction  are crucial factors for success in the Food and Beverage (F&B) industry. This allow for better services and finding area for improvement. Thus, this project aimed to uncover insights into customer demographics, visit patterns, order preferences, spending habits, perception of various factors (ambiance, pricing, service, etc.), and the relationship between satisfaction and repeat purchase intention.

## Data Source

This dataset was acquired from [Kaggle: Starbucks Customer Survey](https://www.kaggle.com/datasets/mahirahmzh/starbucks-customer-retention-malaysia-survey/data). 

The dataset contains responses from 122 customers and includes information such as gender, age, employment status, income level, visit frequency, order preferences, spending patterns, and satisfaction ratings.

## Business Questions
1. Customer Demographic
- What is our customer demographic?
- How often do most of the customer in our dataset visit Starbucks?
- Is there a difference in frequency of visit based on demographic?
- What is the characteristic of our regular customer?
2. Customer behaviour/preferences
- What is most preferred order option by our customer?
- How much time do customer typically spend for each visit?
- How much do customer opt to spend per visit?
- What is the most commonly purchased item by the customer?
- Does the average spending per visit differ across (i)order option, (ii)visit duration, and (iii)type of frequently purchased item?
3. Customer perception/satisfaction
- What is the average customer rating of different factors?
- How does customer satisfaction differ across customer demographic?
- Does customer score rating correlate with their decision for repeat purchases?

## Analysis Approach

The analysis follows a structured approach, divided into three main sections:

1. **Customer Demographic Analysis**: This section explores the customer demographic characteristics, including gender, age, employment status, income level, and proximity to the nearest franchise. It provides insights into the composition of the customer base and identifies potential target segments.  

2. **Customer Behavior and Preference Analysis**: This section delves into customer behavior and preferences, analyzing factors such as order options (dine-in, take-away, drive-thru), visit duration, average spending per visit, and frequently purchased items. It aims to uncover patterns and trends in customer behavior and identify opportunities for tailored product offerings and pricing strategies.  

3. **Customer Perception and Satisfaction Analysis**: This section focuses on customer perception and satisfaction levels, examining ratings for various factors such as ambiance, WiFi quality, price range, service quality, and overall satisfaction. It explores the relationship between customer satisfaction and the likelihood of repeat purchases, providing insights for improving the customer experience.

## Sample Analysis Outputs
![Item by Average spend per visit.png](https://github.com/zul-han/starbucks-customer-analysis/blob/main/image/6.%20Item%20by%20Average%20spend%20per%20visit.png?raw=true)  
_Item by average spend per visit_  
![Average spend per visit by visit duration](https://github.com/zul-han/starbucks-customer-analysis/blob/main/image/7.%20Average%20spend%20per%20visit%20by%20Visit%20duration.png?raw=true)  
_Average spend per visit by visit duration_

## Key Findings  
1. **Customer Demographics** 
- Significant portion of the customer are aged 20-29 and employed, with moderate to high income level.
- Frequency of visit by demograpic:
    - `Gender`: A significant portion of both genders visit rarely, but females have a higher concentration in this category. Conversely, males demonstrate more frequent visits (monthly, weekly, daily). 
    - `Age`: The 20-29 age group has the highest visit frequency across all categories, with a notable concentration in "Rarely."  
    This might be due to the high proportion (69%) of customers in this age bracket. Visits across other age groups show minimal variation
    - `Employment Status`: "Employed" customers dominate the "Rarely," "Monthly," and "Weekly" visit categories.  
    This suggests a potential link between visit frequency and purchasing power.
    - `Annual Income`: A large portion (58.2%) of customers have an annual income below RM 25,000 and fall mainly into the "Rarely" visit category. This group also has the highest concentration in "Monthly" visits.
    - `Distance`:  Half the customers reside more than 3 km from the nearest franchise, and a significant portion of them rarely visit. This pattern holds true for customers living within 3 km of a franchise as well.  
    There's no significant difference in visit frequency based solely on proximity to a store. 

2. **Customer Behavior and Preferences**
- Customer behaviour:
    - Order Options: Take away (40.5%) and dine-in (38%) are the most preferred options, followed by drive-thru (16.53%). A small segment (around 5%) has never ordered coffee or may not be a coffee drinker.
    - Visit Duration: Most customers (58.83%) spend less than 30 minutes per visit, with a decreasing number staying for longer durations. 
    - Average Spend per Visit: Nearly half (47.54%) of customers spend less than RM20, with another 36.88% spending between RM20 and RM45. A small segment spends more than RM40, and interestingly, 10% have no coffee purchase history. 
    - Beverage and Accompaniment Preferences: Coffee is the overwhelming favorite beverage choice (68.85%), followed by cold drinks (31.14%). Juices are the least popular. Pastries are the preferred accompaniment (13.11%), followed by sandwiches (6.53%). 
- Relationship between Order Option, Visit Duration, Items frequently purchased, and Average Spending per Visit:  
    - Dine-in, take-away, and drive-thru customers exhibit similar spending patterns, with most spending less than RM40. 
    - There's a weak correlation between visit duration and spending.
    - Customers with longer visits don't necessarily spend significantly more. 
    - Beverage and pastry preferences remain consistent across spending categories.  

3. **Customer Perception and Satisfaction**
- **Overall Rating and Price Perception**:  While historical data is unavailable to assess trends, the average rating for price falls below those for other categories. 
- **Customer Satisfaction Across Demographics**: Overall customer satisfaction ratings cluster around the average (3.471) across most demographics. However, the rating for customers with an annual income between RM100,000 - RM150,000 is below average, but the limited sample size necessitates further investigation with more data. 
- **Customer Satisfaction and Repeat Purchase**: 
Customers that answer 'Yes' for repeat purchases (77%) display a significantly higher average rating (3.64) compared to those who wouldn't (2.89).  
This highlights a positive correlation between customer satisfaction and repeat purchase behavior. The substantial difference (0.75) in average ratings reinforces the notion that customer satisfaction significantly impacts revisit decisions.

## Recommendations
1. **Targetted Marketing and Customer Segmentation**
- Focusing marketing efforts on core customer segments (employed individuals, students, aged 20-39).
-  Looking at most of the customer usually spend less than RM20, we may change the implementation of loyalty program from price based program to frequency based program.
    - May consider a more complex tiered loyalty program that combines both frequency and spending to cater to a wider range of customer behaviors.

2. **Product Offerings**
- Maintaining strong focus on coffee, cold drinks and pastry offerings.
- To tackle most of the customer in 'Rarely' visit frequency, we may introduce seasonal drinks or limited-time offers to give customers a reason to return and try something new.

3. **Pricing Strategies** 
- Implementing targeted promotions or bundled offering focusing on customer in "Less than RM25,000" income category and customer spending "Less than RM20".
- To increase the number of customer spending between RM 20 - RM40 we may introduce premium or limited-edition products at higher price points.

4. **Customer Experience Improvements**  
Enhancing WiFi quality and conduct future customer satisfaction surveys with current rating as baseline.
