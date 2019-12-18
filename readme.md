团队名：<br>
诗人藏夜里<br>
成绩:<br>
初赛A榜第4 - 初赛B榜第5 - 复赛A榜第6 - 复赛B榜第4<br>

目录结构：
目录结构：

Main:  

    chusai:      		# 初赛相关
      data     			# 存放初赛数据集
      model   			# 用于保存代码运行过程中生成的模型
      submit			# 保存所有模型的预测结果以及融合结果
      fusion.ipynb		# 模型融合代码
      LGB_Model_1.ipynb	# 初赛-机器学习方案一代码
      LGB_Model_2.ipynb	# 初赛-机器学习方案二代码
      LGB_Model_3.ipynb	# 初赛-机器学习方案三代码
      LSTM_Model_1.ipynb	# 初赛-深度学习方案一代码
      LSTM_Model_2.ipynb	# 初赛-深度学习方案二代码
      Rule_Model.ipynb		# 初赛-规则+机器学习模型方案代码

	  fusai:				# 复赛相关
      data				# 存放复赛数据集
      model			# 用于保存代码运行过程中生成的模型
      submit			# 保存所有模型的预测结果以及融合结果
      fusion.ipynb		# 模型融合代码
      LGB_Model_1.ipynb	# 复赛-机器学习方案一代码
      LGB_Model_2.ipynb	# 复赛-机器学习方案二代码
      LGB_Model_3.ipynb	# 复赛-机器学习方案三代码
      LSTM_Model_1.ipynb	# 复赛-深度学习方案一代码
      LSTM_Model_2.ipynb	# 复赛-深度学习方案二代码
    
代码执行顺序(上一个运行完再运行下一个)
1. Cars/chusai/ LGB_Model_1.ipynb
2. Cars/chusai/ LGB_Model_2.ipynb
3. Cars/chusai/ LGB_Model_3.ipynb
4. Cars/chusai/ LSTM_Model_1.ipynb & LSTM_Model_1.ipynb   # 同时运行
5. Rule_Model.ipynb
6. fusion.ipynb
7. /fusai/ LGB_Model_1.ipynb
8. /fusai/ LGB_Model_2.ipynb
9. /fusai/ LGB_Model_3.ipynb
10. /fusai/ LSTM_Model_1.ipynb & LSTM_Model_2.ipynb	# 同时运行
11. /fusai/ fusion.ipynb

3.复赛B榜最终生成结果
/fusai/ submit/ fusion_submit_final.csv

