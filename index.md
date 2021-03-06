


![image](/fig/zhengfan.jpg)

#### Zhengfan Wang   
<object>
    <embed>
        <p><a href="https://github.com/zhengfanwang/zhengfan/blob/gh-pages/doc/Zhengfan%20Wang_CV.pdf">CV</a></p>
</object>

#### Email: zhengfanwang@umass.edu    Phone: 202-374-1285    

My training and research for the past 8 years has focused on Bayesian model, variable selection, smoothing process, high dimensional longitudinal data, and clinical trial design. My current research interests include hierarchical models, variable selection in Bayesian model, the linkage between Bayes and frequentist procedures, infectious disease data like COVID19, smoothing process.


### Research

#### Bayesian modeling
##### Bayesian Hierarchical Temporal Sparse Regression Model: Estimation of Stillbirth Rate [Link](https://arxiv.org/abs/2010.03551)

![image](/fig/worldmap.png)

We developed a Bayesian hierarchical temporal sparse regressionmodel for estimating stillbirth rates for all countries from 2000 to 2019. The model combines covariates with a temporal smoothing process so that estimates are data-driven in country-periods with high-quality data and determined by covariates for country-periods with limited or no data. Horseshoepriors are used to encourage sparseness. The model is used by the UN Inter-agency Group for Child Mortality Estimation to monitor the stillbirth rate for all countries. The work is supported by the Bill & Melinda Gates Foundation, UNICEF, and the National Institute of Environmental Health Sciences of the National Institutes of Health. The work is submitted to AOAS and under review. 


#### Variable selection

Horseshoe prior is a Bayesian sparsity prior that encourages shrinkage towards zero of regression coefficients of irrelevant predictors. 
Although the use of horseshoe priors can result in models with good predictive performance, posterior samples in the resulting model fit are not shrunk to zero exactly to inform the exclusion of irrelevant covariates (like LASSO) and obtain a more parsimonious model to be used for predictions. We propose a new approach for variable selection that is based on model fits using horseshoe priors. In the proposed set up, we introduce noise covariates in the model of interest to obtain a distribution of a shrinkage parameter for irrelevant covariates. For each candidate covariate in the model of interest, we propose an exclusion rule based on comparing the estimate shrinkage for the candidate covariate to the distribution obtained from the noise covariates. We use a simulation study to assess the predictive performance of the proposed approach. 

#### Clinical trial design
##### Computation of the Properties of Multi-Stage Clinical Trial Design Based on SCPRT [Link](https://www.longdom.org/open-access/computation-of-the-properties-of-multistage-clinical-trial-design-basedon-scprt-2167-0870-1000274.pdf)
Multi-stage clinical trial allows the trial to stop early for pronounced treatment effect or the lack of it thereof based on data accumulated at the intermediate stage. The sequential conditional probability ratio test (SCPRT) approach is derived based on the concept of discordance probability, namely, the probability that the decision to accept or reject the null hypothesis based on interim data would reverse should the trial continue to the planned end. However, in the existing SCPRTs, the discordance probability, type I error and power are not easy to compute. Here we investigate a simulation based method to compute these quantities and apply them to a real data problem as an illustration.
