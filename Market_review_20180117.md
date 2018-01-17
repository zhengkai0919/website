# Market Review
Kai Zheng
2018/1/17

## Observation
There seems to have a negative relationship with the predicted profit, which reported by the company itself, with the same day stock return.

## Companay profit prodiction and stock return
1. stock pool: 沪深300
2. research purpose: discover the relationship between 业绩快报 and stock return
3. model: daily percentage return = alpha + beta*同比增长率.利润总额
4. result： 
    - corr coefficient: -0.0697
    - alpha: 44.397(***)
    - beta: -0.62(**)

## Conclusion
1. There is no evidence of supporting the higher predicted profit will result higher stock price return at the same reporting day.
2. The reason may be various:
    - The news has already leaked in someway and was overly reflected in the stock price. And when the news finnally comes out, the institutions tend to cash the profit. 
    - Only when the predicted profit exceeds the general belief of profit of this company from market, it will then generate a positive return in the stock price.
     
## Limitation
1. Only returns of the same day as report published is considered
2. There are no control variables in the regression

## Further investigation
1. add control variables
2. divide the stocks into more sections 
