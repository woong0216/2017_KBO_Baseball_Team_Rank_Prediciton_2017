# Data_Analysis-Korea_Baseball_Team_Regression
## 2017 KBO Baseball Team Rank Prediciton
### Propose
- How will the 2017 KBO Baseball rankings be concluded?
- Is Pythagorean winning rate correlated with kbo baseball rankings?
- Which indicator correlates with baseball winning rates? <br/>
- Additional) Compare a player's ERA with a player's winning rate
### Analysis
#### Each method was applied using the R program.
- Linear Regression Method
> To measure correlation coefficients associated with dependent variables <br/>
> Dependent variable: winning rate
<img width="852" alt="Linear Regression" src="https://user-images.githubusercontent.com/63955072/122663874-92be0580-d1d8-11eb-9058-c275501d7afd.PNG">

- Decision Tree Method
> Classification Tree <br/>
> Classification prediction by rank <br/>

![Decision Tree](https://user-images.githubusercontent.com/63955072/122663894-aff2d400-d1d8-11eb-94ef-2bb1819e71e5.png)

- Pythagorean Method
> Building a Pythagorian winning rate model based on scoring and losing points <br/>

![Pythagorean1](https://user-images.githubusercontent.com/63955072/122671696-e5acb280-d202-11eb-8d32-7e3ece2d33f4.PNG)

- Extra) Single Regression 
> We also wanted to confirm that the indicator correlation of the team was consistent in the indicator correlation of the player. <

![단일 회귀 2](https://user-images.githubusercontent.com/63955072/122673783-0aa62300-d20d-11eb-8cf2-239b2165ae89.png)

### Output
- Linear Regression Result

<img width="686" alt="Linear Regression 2" src="https://user-images.githubusercontent.com/63955072/122663890-a5d0d580-d1d8-11eb-8f32-6b19467fc4ee.PNG">

- Decision Tree Result

![Decision Tree 2](https://user-images.githubusercontent.com/63955072/122663901-b84b0f00-d1d8-11eb-9dc8-f846aa27456e.png)

![Decision Tree 3](https://user-images.githubusercontent.com/63955072/122673072-bfd6dc00-d209-11eb-8e1d-9cc41e9c576b.png)

![Decision Tree 4](https://user-images.githubusercontent.com/63955072/122673075-ca917100-d209-11eb-8288-2beebef18c8e.png)
- Pythagorean Result

<img width="958" alt="Pythagorean2" src="https://user-images.githubusercontent.com/63955072/122671584-5d2e1200-d202-11eb-898e-1b7a7a547e52.PNG">

- Correlation Result

![상관관계 3](https://user-images.githubusercontent.com/63955072/122671962-17724900-d204-11eb-95dc-c61e4416cc41.PNG)

<img width="1038" alt="상관관계 1" src="https://user-images.githubusercontent.com/63955072/122671972-22c57480-d204-11eb-8aeb-cdb3e8c2132d.PNG">

<img width="1036" alt="상관관계 2" src="https://user-images.githubusercontent.com/63955072/122671977-2b1daf80-d204-11eb-969c-b3ad2306e47d.PNG">

- Extra) Single Regression 
> Determine the Correlation between ERA and Win Rate <br/>

<img width="982" alt="Relation" src="https://user-images.githubusercontent.com/63955072/122673788-142f8b00-d20d-11eb-875b-24953432409a.PNG">

> Correlation analysis of the winning rate and ERA of Song Jin-woo <br/>
> Song Jin-woo is the most active player in KBO baseball. <br/>
> Because of the largest accumulation of data, it was selected. <br/>

<img width="1025" alt="단일 회귀" src="https://user-images.githubusercontent.com/63955072/122673808-1c87c600-d20d-11eb-8e9e-7172535c972e.PNG">

### Conclusion
- Linear Regression
> The linear regression extracts the correlated coefficients from each variable. <br/>
> The extracted coefficients were used to predict each team's winning rate. <br/>
- Decision Tree
> Build visualizations with 'rpart' package <br/>
> Recall, accruy, etc. of ranking predictions can be found. <br/>
- Pythagorean
> We confirm the correlation between the Pythagorean winning rate and the actual winning rate for 2016. <br/>
> We can also guess the winning percentage in 2017. <br/>
- Correlation
> Extract meaningful independent variables <br/>
> The relationship between team win rate and team defense rate was the highest. <br/>
> The player's winning rate and the player's ERA were also highly correlated. <br/>


