# Simulating-Cauchy-Distribution
Cauchy Distribution, having "UNDEFINED" mean

## Codes
- small sample
- large sample without outliers

## Packages & Modules
This project uses np.random.standard_cauchy to show the cauchy distribution simulation with parameters 0 and 1
- defaultly, cauchy distribution with parameters 0 and 1 is the ration of two standard normal distributions

## Math Info
Cauchy distribution
- undefined mean
- often used in "pathological" - continuous everywhere, differentiable nowhere.
- also the distribution of two things' ratio

## Analysis
Different graph?
- Cauchy distribution has fatty tails
- "np.cauchy" is influenced heavily by the OUTLIERS!
- Therefore, in the "large" code, outliers need to be excluded
