# 🎮 Otonom Hazine Avcısı

<img src="https://github.com/zeynepplbyk/Treasure-Hunter-Game/assets/125740535/1a6509ae-ee40-4bc7-8205-1de57b32fc3c" alt="Treasure Hunter Banner" width="70%" align="center">


---

## 📝 Proje Özeti
**Otonom Hazine Avcısı**, karakterin rastgele oluşturulan bir harita üzerinde hazineleri topladığı bir oyundur. Karakterin amacı, tüm hazineleri en kısa sürede toplamasını sağlayacak algoritmanın tasarlanmasıdır.  

Öne çıkan özellikler:  
- Rastgele harita ve engeller  
- Otonom karakter hareketi  
- Hazine toplama algoritması  
- En kısa yol hesaplama (Dijkstra algoritması)  

---

## 🔧 Yöntem ve Tasarım

**Anahtar Kelimeler:** OOP, C#, Dijkstra, Hazine Toplama, Karakter, Algoritma, Engel, Hareket, Sandık

### 1. Projenin Amacı
Otonom bir karakter tasarlayarak, harita üzerindeki tüm hazineleri en kısa sürede toplamasını sağlamak. Bunun için **Dijkstra algoritması** ve nesneye yönelik programlama teknikleri kullanılmıştır.

### 2. Oyun Mekanikleri
- Karakter engellerden kaçınır  
- Hazine sandıklarını toplar  
- En kısa yol algoritmasını uygular  
- Sis (fog of war) ile harita karakter ilerledikçe açılır  

### 3. Dijkstra Algoritması
- Haritadaki düğümler (node) noktaları, kenarlar (edge) ise bağlantıları temsil eder  
- Karakterin en kısa yolu bulmasını sağlar  
- Hazinelerin hızlı ve etkili şekilde toplanmasını mümkün kılar  

### 4. Karakter Hareket Algoritması
Karakter, bulunduğu konumdan en yakın hazineye ulaşacak şekilde en kısa yolu hesaplar ve otonom şekilde hareket eder.

### 5. Yazılım Mimarisi
- **C#** ve **Nesneye Yönelik Programlama (OOP)** kullanılmıştır  
- OOP prensipleri: Encapsulation, Inheritance, Polymorphism  
- Hazine, engel ve karakter gibi öğeler nesne olarak modellenmiştir  
- Modüler ve tekrar kullanılabilir kod yapısı sağlanmıştır  

### 6. Engellerle Etkileşim
- Karakter hareketli engellerle karşılaştığında en uygun yolu seçer  
- Otonom hareket algoritması engelleri atlatmak için strateji uygular  

### 7. Deneyler ve Performans
- Farklı harita boyutları ve rastgele yerleştirilen hazineler ile test edilmiştir  
- Algoritma her boyutta verimli çalışmıştır  
- OOP yapısı kodun okunabilirliğini ve performansını artırmıştır  

---

## 📊 Sonuçlar
- Karakter, otonom olarak hazineleri toplar  
- Dijkstra algoritması ile en kısa yol sağlanır  
- OOP tasarımı modülerlik ve bakım kolaylığı sunar  

---

## 🖼 Oyun Görüntüleri

<img src="https://github.com/zeynepplbyk/Treasure-Hunter-Game/assets/125740535/a57f8eca-a063-4ee3-87d5-75b6fe768b50" alt="Oyun Görüntü 1" width="60%">
<img src="https://github.com/zeynepplbyk/Treasure-Hunter-Game/assets/125740535/5ae316a6-5706-40d7-affd-2a9773ffe066" alt="Oyun Görüntü 2" width="60%">
<img src="https://github.com/zeynepplbyk/Treasure-Hunter-Game/assets/125740535/28a10435-6f24-44db-8471-8c2d8dc9a6ed" alt="Oyun Görüntü 3" width="60%">
<img src="https://github.com/zeynepplbyk/Treasure-Hunter-Game/assets/125740535/ba3963c2-6df8-4cd5-93dd-c2a772ed6c4d" alt="Oyun Görüntü 4" width="60%">

---

## 🔗 Kaynaklar
1. [C# Dokümantasyonu](https://learn.microsoft.com/en-us/dotnet/csharp/)  
2. [Unity Learn](https://learn.unity.com/)  
3. [OOP Kavramları](https://www.w3schools.com/cs/cs_oop.php)  
4. [Dijkstra Algoritması Video](https://youtu.be/CUQemt6F0PQ?si=zwaqSrj-9ShCNDB8)  
5. [Unity Asset Store](https://assetstore.unity.com/)  
