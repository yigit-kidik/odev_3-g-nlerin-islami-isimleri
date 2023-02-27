# odev_3-g-nlerin-islami-isimleri

gun_sayisi: int = int(input("Lütfen 1-7 arasında bir sayı giriniz: "))

if (gun_sayisi > 7) or (gun_sayisi < 0):
    print("Girmiş oldunuz sayı 7 den büyük olamaz")
elif gun_sayisi == 1:
    print("Yevmu’l-İs̠neyn")
elif gun_sayisi == 2:
    print("Yevmu’s̠-S̠ülās̠ā’")
elif gun_sayisi == 3:
    print("	Yevmu’l-Erbi‘ā’")
elif gun_sayisi == 4:
    print("Yevmu’l-Hamīs")
elif gun_sayisi == 5:
    print("Yevmu’l-Cumu'a")
elif gun_sayisi == 6:
    print("Yevmu’s-Sebt")
elif gun_sayisi == 7:
    print("	Yevmu’l-Eḥad")
