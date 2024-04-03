# Pengembangan Infrastruktur Jaringan

## Deskripsi

Repository ini berisi review dan saran pengembangan infrakstruktur jaringan berupa topologi beserta deskripsi yang dijelaskan dalam paper-paper berikut:

1. **Sistem Perekam Detak Jantung Berbasis IoT**

   - Paper: [Sistem Perekam Detak Jantung Berbasis Internet of Things (IoT) dengan Menggunakan Pulse Heart Rate Sensor](https://ejournal.unp.ac.id/index.php/jtev/article/view/116677)
   - Deskripsi: Paper ini membahas pengembangan sistem perekam detak jantung berbasis IoT dengan menggunakan sensor Pulse Heart Rate.
   - Saran Pengembangan Infrastruktur Jaringan: Topologi jaringan yangz sesuai mungkin melibatkan perangkat IoT yang terhubung secara nirkabel ke sebuah gateway IoT. Gateway ini kemudian dapat terhubung ke cloud atau server lokal untuk pemrosesan data dan penyimpanan.

2. **Deteksi Anomali Serangan Brute Force dalam IDS**

   - Paper: [Utilizing neural networks with CICIDS2018 dataset for detecting brute force attack anomalies in intrusion detection systems](https://www.iocscience.org/ejournal/index.php/mantik/article/view/4919)
   - Deskripsi: Paper ini membahas penggunaan jaringan saraf tiruan (neural networks) dengan dataset CICIDS2018 untuk mendeteksi anomali serangan brute force dalam sistem deteksi intrusi (IDS).
   - Saran Pengembangan Infrastruktur Jaringan: Topologi jaringan yang sesuai mungkin melibatkan perangkat IDS yang ditempatkan di berbagai titik dalam jaringan untuk memantau lalu lintas data. Perangkat ini dapat terhubung ke server pusat atau cloud untuk analisis data menggunakan teknik neural networks.

3. **Sistem Kontrol Otomatis untuk Akuarium Ikan Hias**
   - Paper: [Prototype of Automatic Control System for Water Temperature and Acidity in Ornamental Fish Aquarium Based on Internet of Things (IOT)](https://ijeeemi.poltekkesdepkes-sby.ac.id/index.php/ijeeemi/article/view/272)
   - Deskripsi: Paper ini membahas pengembangan prototipe sistem kontrol otomatis untuk suhu air dan keasaman dalam akuarium ikan hias berbasis IoT.
   - Saran Pengembangan Infrastruktur Jaringan: Topologi jaringan untuk implementasi ini mungkin melibatkan sensor suhu dan sensor pH yang terhubung secara nirkabel ke gateway IoT di sekitar akuarium. Gateway ini kemudian dapat terhubung ke server atau cloud untuk pemantauan dan pengendalian jarak jauh.

## Topologi Jaringan

![App Screenshot](/Image/3.png)

## Kesimpulan

Dari analisis tiga paper terkait infrastruktur jaringan untuk prototipe IoT, kita dapat melihat bahwa masing-masing prototipe memiliki kebutuhan dan saran pengembangan infrastruktur jaringan yang unik sesuai dengan karakteristiknya.

1. **Sistem Perekam Detak Jantung Berbasis IoT**: Infrastruktur jaringan yang disarankan melibatkan penggunaan perangkat IoT yang terhubung secara nirkabel ke gateway IoT, yang kemudian terhubung ke cloud atau server lokal. Ini memungkinkan pemrosesan dan penyimpanan data detak jantung secara efisien.

2. **Deteksi Anomali Serangan Brute Force dalam IDS**: Prototipe ini memerlukan infrastruktur jaringan yang mendukung penempatan perangkat IDS di berbagai titik dalam jaringan, dengan koneksi ke server pusat atau cloud untuk analisis data menggunakan teknik neural networks.

3. **Sistem Kontrol Otomatis untuk Akuarium Ikan Hias**: Infrastruktur jaringan disarankan untuk melibatkan sensor suhu dan pH yang terhubung ke gateway IoT di sekitar akuarium, dengan koneksi ke server atau cloud untuk pengendalian jarak jauh.

Kesimpulannya, pengembangan infrastruktur jaringan untuk prototipe IoT harus mempertimbangkan kebutuhan spesifik dari setiap aplikasi dan memastikan bahwa topologi jaringan mendukung komunikasi yang efisien antara perangkat IoT, gateway, dan server/cloud. Dengan infrastruktur yang tepat, prototipe tersebut dapat berfungsi dengan baik dan memberikan manfaat yang diinginkan kepada pengguna.

## Instruksi

- Gambar topologi jaringan dapat dilihat di atas.
- Paper-paper yang terkait juga dapat diakses melalui tautan yang disediakan.
- Untuk informasi lebih lanjut, silakan lihat detail pada masing-masing paper.
