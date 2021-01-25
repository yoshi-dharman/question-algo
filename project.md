Project 1 =======================================================
1.STORE var "jam" with user input (int)
2.STORE var "detik"

3.CALCULATE "jam" times 3600
4.SET "detik" value with calculation result
5.DISPLAY "detik(var)" + " detik"


Project 2 =======================================================
1.STORE var "a" with user input (int)
2.STORE var "b" with user input (int)

3.IF "a" > "b"
    DO DISPLAY "a" + " nilai terbesar"
  ELSE IF "a" < "b"
    DO DISPLAY "b" + " nilai terbesar"
  ELSE
    DO DISPLAY "nilai pertama sama dengan nilai kedua"


Project 3 =======================================================
1.STORE var "jumlah-traveler" with user input (int)
2.STORE var "harga-tiket" equal 600000 
3.STORE var "tipe-tiket" with user input (string)
4.STORE var "total"

5.CALCULATE "jumlah-traveler" TIMES "harga-tiker"
6.SET "total" value with calculation result
7.IF "tipe-tiket" equal "two-way"
    DO CALCULATION "total" equal "total" TIMES 2
8.DISPLAY "Harga yang harus dibayar sebesar "+ "total"


Project43 =======================================================
1.STORE var "n" with user input (int)
1.STORE var "i" equal 1

3.WHILE "i" <= "n"
    DO DISPLAY "i "
    ADD "i" by 1


Project 5 =======================================================
1.STORE var "n" with user input (int)
1.STORE var "i" equal 1

3.WHILE "i" <= "n"
    DO IF "i" MODULUS 3 equal 0
        DO DISPLAY "FIZZ"
       ELSE IF "i" MODULUS 5 equal 0
        DO DISPLAY "BUZZ"
    ADD "i" by 1