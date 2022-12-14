# LazyFCA
Homework project on course OSDA  
Achievement:  
Reconstructed the dataset after extracting its features.  
Rewrote the existing pipeline code using numpy and achieved better running speed.  
Compared existing algorithms with a variety of mainstream algorithms. 
* Basic achievements (5-6 pts.)
  * [x] Find a dataset for binary classification:\
  _Ideal dataset would be: openly available, with various datatypes (numbers, categories, graphs, etc),
  with hundreds of rows_;
  * [x] Describe scaling (binarization) strategy for the dataset features,
  * [x] Describe prediction quality measure best suited for the dataset\
  _(e.g. accuracy, f1 score, or any measure that you find reasonable)_,
  * [x] Adapt the pipeline from lazyfca.ipynb to your task.
* (Very) good solution (7-8 pts.):
  * [x] Improve the baseline algorithm:
    * [ ] Achieve better asymptotic time complexity;
    * [x] Improve the runtime of examples comparison:
    * [ ] Rewrite the intersections of sets into the intersection of the corresponding bitmasks. Would it make the algorithm faster?\
    _(numpy, bitarray, and other python packages may be of help)_;
    * [ ] Modify the algorithm to achieve better quality of predictions.
    * [ ] Or simply design a new lazy algorithm to beat the baseline\
    _in terms of algorithmic time complexity, runtime, and prediction quality_;
  * [x] Compare the proposed algorithm with at least 2  popular rule-based models\
  _i.e. decision tree, random forest, XGBoost, CatBoost in terms of runtime and prediction quality_.
* Perfect solution (9-10 pts.)
  * [ ] Incorporate pattern structures into the pipeline to avoid the scaling (binarization);
  * [ ] Test the proposed algorithm on more datasets (at least 3 others);
  * [ ] Compare the proposed algorithm with at least 3  popular rule-based models.
