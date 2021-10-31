# Insertion-Sort

[22,27,16,2,18,6]

1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]

2) Big-O gösterimini yazınız.
En küçük sayıyı bulmak için n tane sayıyı yani bütün diziyi gezdik.
En küçük sayıyı bulduktan sonra dizide bütün sayılara bakmak yerine bulduğumuz sayıyı işleme dahil etmezsek n-1 tane işlem yapacak oluruz.
Her seferinde n-1 işlem yapacağımızdan n+(n-1)+(n-2)+....+1 olur. Bu işlem 1'den n'e kadar olan sayının toplamını verir. Toplamı bulmanın formulü n(n+1)/2'dir. Bu da (n²+n)/2'dir.
Domine eden kısım n² olduğu için O(n²)'dir.

3) Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Average case = O(n²)
Worst case = O(n²)
Best case = O(n)

4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Average case kapsamına girer.

