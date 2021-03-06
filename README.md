## Hybrid Quick Sort + Insertion Sort: Runtime Comparison

Quick sort is a very fast algorithm for sorting. But since it is recursive, it takes comparably same time as insertion sort for "small" arrays. Being iterative and operating by switching elements, insertion sort works better for small arrays which are "almost sorted". Thus by finding an optimum cutoff, we design a hybrid algorithm which partitions the array that needs to be sorted  similar to the quick sort recursively first. It stops when the size of the subarray becomes smaller than a particular cutoff point. When this is the case with all the partitions, insertion sort is applied over the entire array. In this project, we implement this algorithm, and find the optimum cutoff point bu simulation study.

[Report](report_in_markdown.md)
