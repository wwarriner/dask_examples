# Dask Examples

## What is Dask?

[Dask](https://dask.org/) is a library of functions which scale to the resources available by processing small blocks or chunks of data in parallel. Dask scales up or down to whatever resources are available. It will run correctly on both a local laptop or a remote cluster. Dask works by creating a directed acyclic graph (DAG) of block-wise tasks to perform, and assigns those tasks to individual processing units available on the machine. The block-processing nature of Dask means it can work effectively with data that is too large to fit into memory.

Dask has much of the functionality of Pandas, Numpy and Scikit-Learn, and can also work with unstructured data via bags. The library is a collaborative effort by the same people who developed those libraries, so it has years of experience behind its development. It is quite powerful, and worth exploring. We also welcome contributions of additional examples.

## Examples

The examples in the repository so far demonstrate:

 - Large volume image downscaling