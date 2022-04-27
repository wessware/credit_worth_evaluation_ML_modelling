# Credit Worth Evaluation ML Modelling

Intended for this project, is to evaluate the credit worth of customers based on their data.
This model will help money lenders determine if their clients are worth of a credit loans.

## Models

The data is fitted on a Support Vector Machine and an Artificial Neural Network.

## Performannce

Both models score a moderate score.

## Optimization

Further optimization to be done to improve model accuracy

## Further Modelling

Alternative ML models to be built to be used to determine if there can be a better score.

## Advancements

On advanced modelling, we use a synthetic data generator [GENERATIVE ADVERSARIAL NETWORK] to create more data points from the initial dataset and assesses the performance of our models on this 4000 datapoints synthetic data [this is in comparison to the 600 datapoints original dataset].

ANN rmse (original data) ===> 0.39000127674563323
ANN rmse (synthetic data) ===> 0.30305234613896836 (88.5%)

SVM  rmse (original data) ===> 0.4472135954999579
SVM rmse (synthetic data) ===> 0.30276503540974914 (90.8%)

The Support Vector Machine outrightly outperforms the Artificial Neural Network on this test.
