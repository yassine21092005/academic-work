# Randomized linear algebra: Hutchinson trace estimator and Johnson-Lindenstrauss

Python project from the first year at École Polytechnique (pair project; this notebook is my part, in French).

- `randomized_linear_algebra.ipynb`: theory questions (proofs) and numerical experiments, with plots.

**Content**
1. **Hutchinson trace estimator.** Unbiasedness, variance computed for Gaussian and Rademacher random vectors, convergence in the number of samples m (log-log plots), effect of matrix size n, comparison on real data matrices (scikit-learn `digits`, `covtype`, `olivetti_faces`), and checks of the theoretical variance against simulations (ratio close to 1).
2. **Johnson-Lindenstrauss lemma.** Random Gaussian and Rademacher projections, failure probability against the theoretical bound m²·exp(−kε²/8), required projected dimension k as a function of ε, δ and the number of points m.

**Skills:** NumPy, SciPy, Matplotlib, scikit-learn, Monte Carlo methods, probability.
