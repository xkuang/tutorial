### Deeplearning Algorithms tutorial
谷歌的人工智能位于全球前列，在图像识别、语音识别、无人驾驶等技术上都已经落地。而百度实质意义上扛起了国内的人工智能的大旗，覆盖无人驾驶、智能助手、图像识别等许多层面。苹果业已开始全面拥抱机器学习，新产品进军家庭智能音箱并打造工作站级别Mac。另外，腾讯的深度学习平台Mariana已支持了微信语音识别的语音输入法、语音开放平台、长按语音消息转文本等产品，在微信图像识别中开始应用。全球前十大科技公司全部发力人工智能理论研究和应用的实现，虽然入门艰难，但是一旦入门，高手也就在你的不远处！
AI的开发离不开算法那我们就接下来开始学习算法吧！

#### 集成算法(Ensemble Learning)

集成学习(Ensemble Learning)是使用一序列学习器进行学习，并使用某种规则把各个学习结果进行整合从而获得比单个学习器更好的学习效果的一种机器学习方法。集成学习中多个学习器被称为“弱学习器”，如果这些弱学习器都是一个种类的，则被称为是同质的；若这些弱学习器不全是一个种类的，则被称为异质的。一般情况下，集成学习中的多个学习器都是同质的“弱学习器”

集成学习在各个规模的数据集上都有很好的策略。
* 数据集大：划分成多个小数据集，学习多个模型进行组合
* 数据集小：利用Bootstrap方法进行抽样，得到多个数据集，分别训练多个模型再进行组合

集成算法(Ensemble Learning)主要包括:

* Boosting
* Bagging
* AdaBoost
* 堆叠泛化（混合）
* GBM 算法
* GBRT 算法
* 随机森林

