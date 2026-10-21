# Shart operatorlari (if, elif, else)

## if01

Allamurodning yoshi berilgan. Agar yoshi 18 yoki undan katta bo'lsa "Voyaga yetgan", aks holda "Voyaga yetmagan" matnini qaytaring.

**Misol 1:**

```Python
Kirish: yosh=26
Chiqarish: "Voyaga yetgan"
```

**Misol 2:**

```Python
Kirish: yosh=16
Chiqarish: "Voyaga yetmagan"
```

---

## if02

Allamurodning xonadon raqami berilgan. Agar raqam juft bo'lsa "Juft", aks holda "Toq" matnini qaytaring.

**Misol 1:**

```Python
Kirish: n=48
Chiqarish: "Juft"
```

**Misol 2:**

```Python
Kirish: n=347
Chiqarish: "Toq"
```

---

## if03

Allamurodning imtihon bali berilgan. Agar bali 60 yoki undan yuqori bo'lsa "O'tdi", aks holda "Yiqildi" matnini qaytaring.

**Misol 1:**

```Python
Kirish: ball=87
Chiqarish: "O'tdi"
```

**Misol 2:**

```Python
Kirish: ball=54
Chiqarish: "Yiqildi"
```

---

## if04

Allamurodning hisobidagi pul va kitob narxi berilgan. Agar pul yetarli bo'lsa, kitob sotib olingandan keyingi qoldiqni qaytaring, aks holda hisobdagi pulni o'zgarishsiz qaytaring.

**Misol 1:**

```Python
Kirish: balans=100000, narx=28000
Chiqarish: 72000
```

**Misol 2:**

```Python
Kirish: balans=20000, narx=28000
Chiqarish: 20000
```

---

## if05

Allamurodning kunlik foydasi berilgan. Agar u musbat bo'lsa "Foyda", manfiy bo'lsa "Zarar", nolga teng bo'lsa "Nol" matnini qaytaring.

**Misol 1:**

```Python
Kirish: foyda=150000
Chiqarish: "Foyda"
```

**Misol 2:**

```Python
Kirish: foyda=-20000
Chiqarish: "Zarar"
```

**Misol 3:**

```Python
Kirish: foyda=0
Chiqarish: "Nol"
```

---

## if06

Allamurodning yoshi va akasining yoshi berilgan. `max()` funksiyasidan foydalanmasdan kattaroq yoshni qaytaring.

**Misol 1:**

```Python
Kirish: a=26, b=29
Chiqarish: 29
```

**Misol 2:**

```Python
Kirish: a=26, b=21
Chiqarish: 26
```

---

## if07

Hafta kuni raqami berilgan (1 — dushanba, 7 — yakshanba). Agar kun 1–5 oralig'ida bo'lsa "Ish kuni", 6 yoki 7 bo'lsa "Dam olish kuni", aks holda "Noto'g'ri kun" matnini qaytaring.

**Misol 1:**

```Python
Kirish: kun=3
Chiqarish: "Ish kuni"
```

**Misol 2:**

```Python
Kirish: kun=7
Chiqarish: "Dam olish kuni"
```

**Misol 3:**

```Python
Kirish: kun=9
Chiqarish: "Noto'g'ri kun"
```

---

## if08

Soat berilgan (0–23). Allamurodning yordamchi dasturi shu soatga mos salom bersin: 6–11 "Xayrli tong", 12–17 "Xayrli kun", 18–22 "Xayrli kech", qolgan hollarda "Xayrli tun".

**Misol 1:**

```Python
Kirish: soat=8
Chiqarish: "Xayrli tong"
```

**Misol 2:**

```Python
Kirish: soat=14
Chiqarish: "Xayrli kun"
```

**Misol 3:**

```Python
Kirish: soat=20
Chiqarish: "Xayrli kech"
```

**Misol 4:**

```Python
Kirish: soat=2
Chiqarish: "Xayrli tun"
```

---

## if09

Toshkentdagi havo harorati berilgan. Harorat 0 dan past bo'lsa "Muzlatuvchi", 0–15 bo'lsa "Sovuq", 16–25 bo'lsa "Iliq", 25 dan yuqori bo'lsa "Issiq" matnini qaytaring.

**Misol 1:**

```Python
Kirish: harorat=-5
Chiqarish: "Muzlatuvchi"
```

**Misol 2:**

```Python
Kirish: harorat=10
Chiqarish: "Sovuq"
```

**Misol 3:**

```Python
Kirish: harorat=22
Chiqarish: "Iliq"
```

**Misol 4:**

```Python
Kirish: harorat=38
Chiqarish: "Issiq"
```

---

## if10

Allamurod uchta do'kondagi telefon narxini bildi. `min()` funksiyasidan foydalanmasdan eng arzon narxni qaytaring.

**Misol 1:**

```Python
Kirish: a=4200000, b=3950000, c=4100000
Chiqarish: 3950000
```

**Misol 2:**

```Python
Kirish: a=100, b=200, c=50
Chiqarish: 50
```

---

## if11

Allamurodning test bali (0–100) berilgan. Bahoni qaytaring: 86–100 → 5, 71–85 → 4, 56–70 → 3, 0–55 → 2. Ball 0–100 oralig'ida bo'lmasa "Noto'g'ri ball" matnini qaytaring.

**Misol 1:**

```Python
Kirish: ball=92
Chiqarish: 5
```

**Misol 2:**

```Python
Kirish: ball=78
Chiqarish: 4
```

**Misol 3:**

```Python
Kirish: ball=60
Chiqarish: 3
```

**Misol 4:**

```Python
Kirish: ball=40
Chiqarish: 2
```

**Misol 5:**

```Python
Kirish: ball=105
Chiqarish: "Noto'g'ri ball"
```

---

## if12

Yil berilgan. Agar yil kabisa bo'lsa 366, aks holda 365 (yildagi kunlar soni) qaytaring. Yil 4 ga bo'linsa va 100 ga bo'linmasa yoki 400 ga bo'linsa, u kabisa yili hisoblanadi.

**Misol 1:**

```Python
Kirish: yil=2000
Chiqarish: 366
```

**Misol 2:**

```Python
Kirish: yil=2026
Chiqarish: 365
```

**Misol 3:**

```Python
Kirish: yil=1900
Chiqarish: 365
```

---

## if13

Allamurodning maoshi berilgan. Shartli soliq tizimi bo'yicha soliq summasini butun son ko'rinishida qaytaring: 3000000 gacha (shu summa ham kiradi) — soliq yo'q; 3000000 dan 10000000 gacha — 3000000 dan oshgan qismning 12 foizi; 10000000 dan yuqori — 840000 + 10000000 dan oshgan qismning 20 foizi. Foizni `* foiz // 100` ko'rinishida hisoblang.

**Misol 1:**

```Python
Kirish: maosh=2500000
Chiqarish: 0
```

**Misol 2:**

```Python
Kirish: maosh=6500000
Chiqarish: 420000
```

**Misol 3:**

```Python
Kirish: maosh=12000000
Chiqarish: 1240000
```

---

## if14

Allamurod taksi xizmatidan foydalanmoqda. Dastlabki 3 km — 10000 so'm, keyingi har bir km — 2500 so'm. Agar masofa 20 km dan oshsa, umumiy narxga 10 foiz chegirma beriladi (`* 90 // 100`). Masofa (butun km) berilgan, to'lov summasini qaytaring.

**Misol 1:**

```Python
Kirish: km=2
Chiqarish: 10000
```

**Misol 2:**

```Python
Kirish: km=10
Chiqarish: 27500
```

**Misol 3:**

```Python
Kirish: km=30
Chiqarish: 69750
```

---

## if15

Allamurod bog'ida uchburchak gulzor qilmoqchi, tomonlari a, b, c berilgan. Agar bu tomonlardan uchburchak yasab bo'lmasa "Uchburchak emas", uchala tomon teng bo'lsa "Teng tomonli", ikki tomoni teng bo'lsa "Teng yonli", aks holda "Turli tomonli" matnini qaytaring.

**Misol 1:**

```Python
Kirish: a=5, b=5, c=5
Chiqarish: "Teng tomonli"
```

**Misol 2:**

```Python
Kirish: a=5, b=5, c=8
Chiqarish: "Teng yonli"
```

**Misol 3:**

```Python
Kirish: a=3, b=4, c=5
Chiqarish: "Turli tomonli"
```

**Misol 4:**

```Python
Kirish: a=1, b=2, c=5
Chiqarish: "Uchburchak emas"
```

---

## if16

Allamurodning vazni (kg) va bo'yi (m) berilgan. BMI = vazn / bo'y² ni hisoblang. BMI 18.5 dan kichik bo'lsa "Vazn yetishmaydi", 25 dan kichik bo'lsa "Normal", 30 dan kichik bo'lsa "Ortiqcha vazn", aks holda "Semizlik" matnini qaytaring.

**Misol 1:**

```Python
Kirish: vazn=74, boy=1.78
Chiqarish: "Normal"
```

**Misol 2:**

```Python
Kirish: vazn=55, boy=1.78
Chiqarish: "Vazn yetishmaydi"
```

**Misol 3:**

```Python
Kirish: vazn=85, boy=1.78
Chiqarish: "Ortiqcha vazn"
```

**Misol 4:**

```Python
Kirish: vazn=100, boy=1.78
Chiqarish: "Semizlik"
```

---

## if17

Oy raqami berilgan. Fasl nomini qaytaring: 12, 1, 2 — "Qish"; 3–5 — "Bahor"; 6–8 — "Yoz"; 9–11 — "Kuz". Boshqa qiymatlar uchun "Noto'g'ri oy" qaytaring. Allamurod mart oyida tug'ilgan — bu "Bahor".

**Misol 1:**

```Python
Kirish: oy=3
Chiqarish: "Bahor"
```

**Misol 2:**

```Python
Kirish: oy=1
Chiqarish: "Qish"
```

**Misol 3:**

```Python
Kirish: oy=10
Chiqarish: "Kuz"
```

**Misol 4:**

```Python
Kirish: oy=13
Chiqarish: "Noto'g'ri oy"
```

---

## if18

ax² + bx + c = 0 tenglamaning koeffitsiyentlari berilgan. Agar a = 0 bo'lsa "Kvadrat tenglama emas" matnini qaytaring. Aks holda diskriminantni (D = b² − 4ac) hisoblang va haqiqiy ildizlar sonini qaytaring: D > 0 bo'lsa 2, D = 0 bo'lsa 1, D < 0 bo'lsa 0.

**Misol 1:**

```Python
Kirish: a=1, b=-5, c=6
Chiqarish: 2
```

**Misol 2:**

```Python
Kirish: a=1, b=2, c=1
Chiqarish: 1
```

**Misol 3:**

```Python
Kirish: a=1, b=1, c=5
Chiqarish: 0
```

**Misol 4:**

```Python
Kirish: a=0, b=2, c=1
Chiqarish: "Kvadrat tenglama emas"
```

---

## if19

Allamurod bankdan kredit so'ramoqda. Yosh, maosh va oylik to'lov berilgan. Agar yosh 21 dan kichik yoki 60 dan katta bo'lsa "Yosh mos emas" matnini qaytaring. Agar oylik to'lov maoshning yarmidan ko'p bo'lsa "Daromad yetarli emas" matnini qaytaring. Aks holda "Kredit tasdiqlandi" matnini qaytaring.

**Misol 1:**

```Python
Kirish: yosh=26, maosh=6500000, tolov=2500000
Chiqarish: "Kredit tasdiqlandi"
```

**Misol 2:**

```Python
Kirish: yosh=26, maosh=6500000, tolov=3500000
Chiqarish: "Daromad yetarli emas"
```

**Misol 3:**

```Python
Kirish: yosh=19, maosh=6500000, tolov=1000000
Chiqarish: "Yosh mos emas"
```

---

## if20

Sana kun, oy va yil ko'rinishida berilgan. Agar bunday sana mavjud bo'lsa "To'g'ri sana", aks holda "Noto'g'ri sana" matnini qaytaring. Oylardagi kunlar soni va kabisa yilini hisobga oling (fevral kabisa yilida 29 kun, aks holda 28 kun; aprel, iyun, sentyabr, noyabr — 30 kun; qolganlari — 31 kun).

**Misol 1:**

```Python
Kirish: kun=15, oy=3, yil=2000
Chiqarish: "To'g'ri sana"
```

**Misol 2:**

```Python
Kirish: kun=29, oy=2, yil=2000
Chiqarish: "To'g'ri sana"
```

**Misol 3:**

```Python
Kirish: kun=29, oy=2, yil=2026
Chiqarish: "Noto'g'ri sana"
```

**Misol 4:**

```Python
Kirish: kun=31, oy=4, yil=2026
Chiqarish: "Noto'g'ri sana"
```

