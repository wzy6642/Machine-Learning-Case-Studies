# Machine-Learning-Case
## trip
本项目是数据的EDA探索，针对自行车共享数据集`2015_trip_data`进行探索性数据分析。这个数据集的特征如下表所示：

特征名称  | 说明|
| :------------: |:---------------:|
trip_id  | 为每个行程分配的唯一ID |
starttime  | 在PST中，行程开始的日期和时间 |
stoptime  | 在PST中，行程结束的日期和时间 |
bikeid  | 每辆自行车的ID |
tripduration  | 以秒为单位的行程时间 |
from_station_name  | 行程起始站名 |
to_station_name  | 行程终止站名 |
from_station_id  | 行程起始站ID |
to_station_id  | 行程终止站ID |
usertype  | 数据可以是以下任意一种：短期通行证持有者或会员 |
gender  | 骑手性别 |
birthyear  | 骑手出生年份 |

分别观察了数据集的数据分布、时间序列成分、度量测度中心、离群样本、相关性、t-分布、中心极限定理等。
## Concrete
本项目是数据的回归预测，针对混凝土抗压强度数据集`Concrete_Data`进行样本的混凝土抗压强度预测。这个数据集的特征如下表所示：

特征名称  | 说明|
| :------------: |:---------------:|
cement_component  | 水泥(组分1)(千克/立方米混合物) |
furnace_slag  | 高炉矿渣(组分2)(千克/立方米混合物) |
flay_ash  | 粉煤灰(组分3)(千克/立方米混合物) |
water_component  | 水(组分4)(千克/立方米混合物) |
superplasticizer  | 减水剂(组分5)(千克/立方米混合物) |
coarse_aggregate  | 粗骨料(组分6)(千克/立方米混合物) |
fine_aggregate  | 细骨料(组分7)(千克/立方米混合物) |
age  | 龄期(天) |
concrete_strength  | 混凝土抗压强度(MPa,兆帕) |

先对特征之间，特征与label之间的一致性进行观察，然后选取一致性较高的特征进行分析，基于R^2指标，分别用线性回归/岭回归/Lasso回归/ElasticNet/梯度boosting回归/支持向量机对数据集做单变量与多变量的回归预测分析。
## Yahoo
本项目是针对股票作时间序列分析与预测，针对数据集为雪人2017年全年的数据集。这个数据集的特征如下表所示：

特征名称  | 说明|
| :------------: |:---------------:|
date  | 日期  |
open  | 开盘价  |
high  | 最高价  |
close  | 收盘价  |
low  | 最低价  |
volume  | 成交量  |
price_change  | 价格变动   |
p_change  | 涨跌幅   |
ma5  | 5日均价  |
ma10  | 5日均价  |
ma5  | 10日均价  |
ma20  | 20日均价  |
v_ma5  | 5日均量  |
v_ma10  | 10日均量  |
v_ma20  | 20日均量  |
