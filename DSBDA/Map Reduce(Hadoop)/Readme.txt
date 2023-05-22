	
# create input2000 folder in home and paste the csv file in it.

   1. jps

# START HADOOP by start-all.sh

# Copying input to HDFS file System by following command:

	2. hdfs dfs -put ~/input2000 /
	
# Then to perform Map and Reduce:
	
	3. hadoop jar analyzelogs.jar /input2000 /output2000
	
# See the Output by following command:

	4. hdfs dfs -cat /output2000/part-00000
