## Project description
You are an analyst at a big online store. Together with the marketing department, you've compiled a list of hypotheses that may help boost revenue. You need to prioritize these hypotheses, launch an A/B test, and analyze the results.

## Purpose 
To identify:
+ The prioritize for these hypotheses
+ Launch an A/B test
+ Analyze the results

## Action Plan
Part 1 for priortizing hypotheses
  + Used RICE and ICE priortizing framework
  + Do analyse and conclusion
  
Part 2 for A/B testing
  + Preprocessing : Review and analyse the given data provided, then, fix the data and enrich it for later use in project
  + Analyse data : Analyse the data
  + Conclusion : Create overall conclusion

## Description of the data
1. hypotheses_us.csv
    + Hypotheses — brief descriptions of the hypotheses
    + Reach — user reach, on a scale of one to ten
    + Impact — impact on users, on a scale of one to ten
    + Confidence — confidence in the hypothesis, on a scale of one to ten. Higher more intense.
    + Effort — the resources required to test a hypothesis, on a scale of one to ten. Higher more intense.
      
2. orders_us.csv
    + transactionId — order identifier
    + visitorId — identifier of the user who placed the order
    + date — of the order
    + revenue — from the order
    + group — the A/B test group that the user belongs to

3. visits_us.csv
    + date — date
    + group — A/B test group
    + visits — the number of visits on the date specified in the A/B test group specified
