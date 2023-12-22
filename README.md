1.	Normalizasyon ile standardizasyon arasındaki farklar

Normalizasyon, verileri 0 ve 1 arasında yeniden ölçekler. Bu işlem tüm parametrelerin aynı pozitif ölçeğe sahip olması gereken bazı durumlarda yararlı olabilir. Ancak aykırı değerlerin (outliers) kaybolmasına yol açar. En sık kullanılan normalizasyon yöntemlerinden biri olan Feature Scaling, (Özellik Ölçekleme veya Min-Max Normalizasyonu) normal dağılımı esas alır ve her bir değerin ortalamadan olan uzaklığının standart sapmaya oranı ile bulunur. Bu metot ile değişkenlerin farklı ortalamalarda ve standart sapmaya sahip olmasına izin verilir ancak aynı aralıkta olmaları şartıyla.

Standardizasyon ise veriyi aynı ortalama (0) ve aynı standart sapmaya (1) sahip olması için yeniden ölçeklendirilmesidir. Çok değişkenli analizlerde değişkenlerin standartlaştırılması doğru analiz için önemli rol oynamaktadır. Farklı ölçeklerde ölçülen değişkenler analize eşit katkıda bulunamaz. Örneğin 0–100 aralığında ve 0–1 aralığında yer alan iki feature üzerinde standardizasyon gerçekleştirilmezse 0–100 aralığındaki değişkenin modeldeki ağırlığı daha fazla olacaktır. Verileri karşılaştırılabilir ölçeklere dönüştürmek bu sorunu önleyebilir. Veri standardizasyonu ile bu ölçeklendirmeyi sağlayabiliriz.
