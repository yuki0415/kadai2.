# kadai2.
ノード名が「count」,パブリッシャが「count_up」
rospy.Publisherを作り定期的にデータを投げる
あらかじめrostopicを立ち上げておく.rosnode list とlistでノードとトピックの確認をするそしてrostpic echo でcount_upからデータを取り出す.
rospy.Subscriberを使いtwice.pyを作る.twice.pyを実行すると2倍になった数字が端末上に表示される.
