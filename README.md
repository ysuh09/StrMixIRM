# StrMixIRM
## Description
This repository includes R code and Mplus syntax for fitting Structured Mixture Item Response Models (StrMixIRMs) using the reparameterization mentioned in 
Lee, M., Suh, Y.S., & Jeon, M. (2024). Item Response Analysis of a Structured Mixture Item Response Model with mirt Package in R. _Psych_, 6(1), 812-835. (https://doi.org/10.3390/psych6010023)

At present, the resposity contains implementions of the following types of StrMixIRMs:
* Unidimensional StrMixIRMs
* Multidimensinal StrMixIRMs 
* Dichotomous StrMixIRMs
* Polytomous StrMixIRMs
  
For each type of of StrMixIRM above, the following measurement models are possible:
* Rasch Models
* 1-parameter logistic (1PL) Models
* 2-parameter logistic (2PL) Models with item slopes on $\theta_{ih}$
* 2-parameter logistic (2PL) Models with slope differentiation parameters

## Table of contents
* [Data](#data)
* [Installations](#installations)
* [Folder Structure](#folder-structure)
* [Contributing](#contributing)
* [Questions?](#questions)
* [Citation](#citation)

## Data
The ECPE dataset may be found either within this repository in the [ECPE folder]() or within the GDINA package as shown [here](https://search.r-project.org/CRAN/refmans/GDINA/html/ecpe.html). 
The Verbal Aggression dataset may be found either within this repository in the [Verbal Aggression folder]() or in the lme4 package as shown [here](https://rdrr.io/cran/lme4/man/VerbAgg.html). 

## Installations 
* Install [R](https://cran.r-project.org/bin/windows/base/)
* Install [mirt package in R](https://github.com/philchalmers/mirt)
> [!IMPORTANT]  
> Please install mirt directly from the mirt github repository (https://github.com/philchalmers/mirt) following the instructions outlined as opposed to the CRAN repository for all codes to run properly
* Download [Mplus](https://www.statmodel.com/platforms.shtml)
> [!NOTE]  
> Mplus is a commerical software. Free demo versions are available but the syntaxes
in this repository are outside the scope of the capabilities of the demo version

## Folder Structure
* [ECPE]()
  * [Data]()
  * [R_mirt]()
  * [Mplus]()
      * StrMixIRT using [linear constraints]()
      * StrMixMIRT using [interaction effects]()
  * [Organized Results]()
* [Verbal Aggression]()
  * [Data]()
  * [R_mirt]()
  * [Mplus]()
      * StrMixIRT using [linear constraints]()
      * StrMixMIRT using [interaction effects]()
  * [Organized Results]()
  
## Contributing
This is research code. Pull requests and issues are welcome and appreciated!

## Questions?
Please contact the authors below regarding questions pertaining to the code/syntax in this repository
* Minho Lee:  leemino72@gmail.com
* Yon Soo Suh: yon.soo.suh@nwea.org

## Citation
Lee, M., Suh, Y.S., & Jeon, M. (2024). Item Response Analysis of a Structured Mixture Item Response Model with mirt Package in R. _Psych_, 6(1), 812-835. 
