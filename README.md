# Ikili_Arama-Binary_Search-
Binary Search, sıralı(sorted) bir veri yapısı için kullanılır. 
Yani algoritmaya aranan veri ve sıralı bir veri yapısı verirsiniz. Algoritma da size önceki örnekteki gibi eğer bulunursa aranan verinin indeksini döner. 
Bunun için önce elimizdeki verinin sıralanması gerekir.
Binary Search algoritmasının zaman karmaşıklığı O(log n)’dir.
Her iterasyonda arama uzayını yarıya indirmek üzere tasarlanmıştır. Öncelikle dizinin ortasındaki değeri aranan değer ile karşılaştırır. 
Eğer aranan değer ortanca değerden küçükse dizinin ikinci yarısını görmezden gelerek ilk yarısında aramaya devam eder. 
Daha sonra tekrar ilk yarının ortanca 
değeri ile karşılaştırır. Eğer aranan değer ortanca değerden küçükse sol yarı, büyükse sağ yarı ile devam eder. Bu şekilde aranan değeri bulana kadar sürer. 
Aranan değer ilk iterasyonda da bulunabilir son iterasyonda da. Ancak Linear Search’den farklı olarak her bir elemanı gezmediği için aranan değeri daha hızlı bulacaktır. 
