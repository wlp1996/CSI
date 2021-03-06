# 实验报告

实验共分三个数据集：fixed、open、semi

## 规则约定

- accuracy/loss中红色线为train，蓝色线为val
- 每个数据集中表现最好（准确率最高/最稳定）一组的序号加粗显示

## fixed

| 序号  | train batch | train Iterations | base Ir | accuracy                                                     | loss                                                         | matrix                                                       |
| :---: | ----------- | ---------------- | ------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
|   0   | 64          | 1000             | 0.05    | ![](https://raw.githubusercontent.com/DmrfCoder/CSI/master/ExperimentalRecord/Selection_005.png) | ![](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_006.png?raw=true) | ![](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Fixed_confusion_matrix_val.png?raw=true) |
|   1   | 64          | 5000             | 0.05    | ![](https://raw.githubusercontent.com/DmrfCoder/CSI/master/ExperimentalRecord/Selection_007.png) | ![](https://raw.githubusercontent.com/DmrfCoder/CSI/master/ExperimentalRecord/Selection_008.png) | ![](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Fixed_confusion_matrix_val1.png?raw=true) |
| **2** | 64          | 3000             | 0.1     | ![](https://raw.githubusercontent.com/DmrfCoder/CSI/master/ExperimentalRecord/Selection_009.png) | ![](https://raw.githubusercontent.com/DmrfCoder/CSI/master/ExperimentalRecord/Selection_010.png) | ![](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Fixed_confusion_matrix_val2.png?raw=true) |
|   3   | 64          | 10000            | 0.1     | ![](https://raw.githubusercontent.com/DmrfCoder/CSI/master/ExperimentalRecord/Selection_031.png) | ![](https://raw.githubusercontent.com/DmrfCoder/CSI/master/ExperimentalRecord/Selection_032.png) | ![](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Fixed_confusion_matrix_val3.png?raw=true) |
|   8   | 64          | 10000            | 0.2     | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_033.png?raw=true) | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_034.png?raw=true) | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Fixed_confusion_matrix_val4.png?raw=true) |
|   9   | 64          | 10000            | 0.05    | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_035.png?raw=true) | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_036.png?raw=true) | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Fixed_confusion_matrix_val5.png?raw=true) |

## open

| 序号  | train batch | train Iterations | base Ir | accuracy                                                     | loss                                                         | matrix                                                       |
| ----- | ----------- | ---------------- | ------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 0     | 64          | 1000             | 0.05    | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_000.png?raw=true) | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_004.png?raw=true) | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Open_confusion_matrix_val.png?raw=true) |
| 1     | 64          | 3000             | 0.1     | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_011.png?raw=true) | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_012.png?raw=true) | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Open_confusion_matrix_val1.png?raw=true) |
| 2     | 64          | 3000             | 0.01    | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_013.png?raw=true) | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_014.png?raw=true) | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Open_confusion_matrix_val2.png?raw=true) |
| 3     | 64          | 3000             | 0.2     | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_015.png?raw=true) | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_016.png?raw=true) | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Open_confusion_matrix_val3.png?raw=true) |
| 4     | 64          | 3000             | 0.25    | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_017.png?raw=true) | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_018.png?raw=true) | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Open_confusion_matrix_val4.png?raw=true) |
| 5     | 64          | 3000             | 0.15    | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_019.png?raw=true) | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_020.png?raw=true) | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Open_confusion_matrix_val5.png?raw=true) |
| 6     | 64          | 5000             | 0.15    | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_021.png?raw=true) | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_022.png?raw=true) | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Open_confusion_matrix_val6.png?raw=true) |
| **7** | 64          | 10000            | 0.15    | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_025.png?raw=true) | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_026.png?raw=true) | ![img](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Open_confusion_matrix_val7.png?raw=true) |

## semi

| 序号  | train batch | train Iterations | base Ir | accuracy                                                     | loss                                                         | matrix                                                       |
| :---: | ----------- | ---------------- | ------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
|   0   | 64          | 1000             | 0.1     | ![](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_001.png?raw=true) | ![](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_003.png?raw=true) | ![](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Semi_confusion_matrix_val0.png?raw=true) |
|   1   | 64          | 10000            | 0.15    | ![](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_027.png?raw=true) | ![](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_028.png?raw=true) | ![](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Semi_confusion_matrix_val1.png?raw=true) |
| **2** | 64          | 10000            | 0.1     | ![](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_029.png?raw=true) | ![](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Selection_030.png?raw=true) | ![](https://github.com/DmrfCoder/CSI/blob/master/ExperimentalRecord/Semi_confusion_matrix_val2.png?raw=true) |







