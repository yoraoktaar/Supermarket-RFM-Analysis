# Supermarket RFM Analysis 🍷🥩🍏🪙🍬

By: Yora Okta Aviani Rahardjo 

## Business Understanding

<span style="font-size:20px; font-family: monospace;">`1. Background`</span>

In facing increasingly intense competition in the supermarket retail industry, companies need to deeply understand customer segmentation. The RFM (Recency, Frequency, Monetary) method is an appropriate approach for analyzing the time of the last purchase, transaction frequency, and the total purchase value of customers. By analyzing customer data from 2012 to 2014 and comparing the effectiveness between customer segments and their responses to marketing campaigns, companies can develop more accurate promotional strategies to enhance loyalty and increase sales.

<span style="font-size:20px; font-family: monospace;">`2. Stakeholder`</span>

1. Management Executive
2. Marketing Team

<span style="font-size:20px; font-family: monospace;">`3. Business Problem`</span>


1. Which customer and product segments contribute the most to revenue?
2. How can we understand customer preferences and value that impact company performance?
3. How effective are marketing campaigns in driving sales?

<span style="font-size:20px; font-family: monospace;">`4. Goals`</span>

1. Identify customer and product segments in the supermarket that significantly contribute to revenue.
2. Analyze customer segmentation using the RFM (Recency, Frequency, Monetary) method.
3. Measure campaign effectiveness and design targeted promotional strategies based on customer segmentation.

## Data Understanding
Is the dataset of Supermarket Customers from 2012 to 2014.

#### People

| Column              | Description                                                   |
| ------------------- | ------------------------------------------------------------- |
| **ID**              | Customer's unique identifier                                  |
| **Year\_Birth**     | Customer's birth year                                         |
| **Education**       | Customer education level                                      |
| **Marital\_Status** | Customer's marital status                                     |
| **Income**          | Customer's yearly household income                            |
| **Kidhome**         | Number of children in customer's household                    |
| **Teenhome**        | Number of teenagers in customer's household                   |
| **Dt\_Customer**    | Date of customer's enrollment with the company                |
| **Recency**         | Number of days since customer's last purchase                 |
| **Complain**        | 1 if the customer complained in the last 2 years, 0 otherwise |

#### Product

| Column               | Description                                |
| -------------------- | ------------------------------------------ |
| **MntWines**         | Amount spent on wine in the last 2 years   |
| **MntFruits**        | Amount spent on fruits in the last 2 years |
| **MntMeatProducts**  | Amount spent on meat in the last 2 years   |
| **MntFishProducts**  | Amount spent on fish in the last 2 years   |
| **MntSweetProducts** | Amount spent on sweets in the last 2 years |
| **MntGoldProds**     | Amount spent on gold in the last 2 years   |

#### Promotion

| Column                | Description                                                            |
| --------------------- | ---------------------------------------------------------------------- |
| **NumDealsPurchases** | Number of purchases made with a discount                               |
| **AcceptedCmp1**      | 1 if the customer accepted the offer in the 1st campaign, 0 otherwise  |
| **AcceptedCmp2**      | 1 if the customer accepted the offer in the 2nd campaign, 0 otherwise  |
| **AcceptedCmp3**      | 1 if the customer accepted the offer in the 3rd campaign, 0 otherwise  |
| **AcceptedCmp4**      | 1 if the customer accepted the offer in the 4th campaign, 0 otherwise  |
| **AcceptedCmp5**      | 1 if the customer accepted the offer in the 5th campaign, 0 otherwise  |
| **Response**          | 1 if the customer accepted the offer in the last campaign, 0 otherwise |

#### Place

| Column                | Description                                                 |
| ----------------------- | ----------------------------------------------------------- |
| **NumWebPurchases**     | Number of purchases made through the company’s website      |
| **NumCatalogPurchases** | Number of purchases made using a catalog                    |
| **NumStorePurchases**   | Number of purchases made directly in stores                 |
| **NumWebVisitsMonth**   | Number of visits to the company’s website in the last month |

### What is RFM?

RFM stands for:

- Recency: How recently a customer made their last purchase.

- Frequency: How often a customer makes purchases within a certain period.

- Monetary: How much money a customer spends on purchases.

The purpose of RFM is to segment customers into categories based on their behavior.

 ## Business Conclusion
Spending per Product Category
Based on Median:

1. Wines (174.5) is the category with the highest spending, indicating large transaction values or regular purchases.
2. Meat Products (67.0) rank second, highlighting their importance in shopping patterns.
3. Gold Products (24.0) play a moderate role, possibly high in value but purchased less frequently.
4. Fish (12.0), Fruits (8.0), and Sweet Products (8.0) have low median spending, likely due to lower prices or less frequent purchases.

Customer Segments (RFM):

1. Champions: Best customers; recent, frequent, and high-value buyers. Their loyalty needs to be maintained.
2. Loyal Customers: Frequent and high-value buyers, though not very recent. Worth keeping and appreciating.
3. At Risk: Previously active but now becoming inactive. Requires approaches to prevent loss.
4. Hibernating: Infrequent and haven’t purchased for a long time. Can be targeted with reactivation campaigns.
5. New Customers: Recently made purchases but not yet regular. Need education and encouragement for repeat buying.
6. Lost Customers: Have been inactive for a very long time. Low potential, can be given low priority.
7. Potential Loyal Customers: Customers showing signs of increased engagement and purchase frequency. With proper nurturing, they can become loyal buyers.

Campaign Effectiveness:

Out of the total customers, 568 people (27.65%) responded to the campaign (responded to at least one campaign), while 1,486 people (72.35%) did not respond at all.
Although the non-responding group is larger, they actually generated a higher total expenditure amounting to 681,283, compared to the group that received the campaign, which only generated 564,358.

Recency (Last Campaign) vs Response:

Customers who responded to the campaign tended to be more recent (interacted more recently) — as indicated by their lower recency values. On the other hand, those who did not respond to the campaign had not made transactions for a longer period (higher recency values).

<span style="font-size:20px; font-family: monospace;">`Recomendation`</span>

1. Champions

    - Provide loyalty programs and exclusive discounts
    
    - Offer premium products or upselling opportunities
    
    - Engage them in brand communities

2. Loyal Customers

    - Send personalized promotions and product education
    
    - Create referral programs
    
    - Organize special events for loyal customers

3. At Risk

    - Send “We Miss You” offers
    
    - Analyze reasons for decline and offer relevant products
    
    - Run win-back programs with special incentives

4. Hibernating

    - Conduct customer satisfaction surveys
    
    - Offer large discounts or bundled packages
    
    - Send engaging and relevant content

5. New Customers

    - Build relationships through product education
    
    - Provide special offers for the next purchase
    
    - Send tips and product reviews

6. Lost Customers

    - Reactivation campaigns with big discounts (if feasible)
    
    - Focus on customers with potential to return
    
    - Remove irrelevant data
      
7. Potential Loyal Customers
    - Identify customers showing signs of increasing engagement
    
    - Provide targeted incentives to encourage more frequent purchases

    - Offer tailored communication based on purchase behavior and preferences





