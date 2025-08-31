Overview Proyek
Proyek ini bertujuan untuk mengeksplorasi dan mengimplementasikan Convolutional Autoencoder (CAE) menggunakan dataset Fashion-MNIST. Autoencoder adalah model jaringan saraf tiruan unsupervised yang dirancang untuk mempelajari representasi data yang efisien, atau yang dikenal sebagai ruang laten. Model ini dilatih untuk mengompresi data masukan dan kemudian merekonstruksinya kembali.

Arsitektur Model
Model yang digunakan dalam proyek ini adalah Convolutional Autoencoder (CAE) yang terdiri dari dua bagian utama:

Encoder: Bagian ini bertanggung jawab untuk mengompresi gambar masukan (28x28 piksel) menjadi representasi yang lebih kecil berdimensi 64 melalui serangkaian lapisan konvolusi.

Decoder: Bagian ini melakukan kebalikan dari proses encoder, yaitu merekonstruksi gambar asli dari representasi 64 dimensi kembali ke ukuran 28x28 piksel.

Dataset
Dataset yang digunakan adalah Fashion-MNIST, yang terdiri dari 70.000 gambar fesyen hitam-putih. Dataset ini berfungsi sebagai pengganti yang lebih menantang dari dataset MNIST klasik.

🔗 Link Dataset: Fashion-MNIST Dataset di Kaggle

Hasil
Proyek ini berhasil menghasilkan:

Kurva Loss: Grafik yang menunjukkan penurunan training loss dan validation loss yang stabil.

Rekonstruksi Gambar: Model mampu merekonstruksi gambar dengan akurat, mempertahankan detail utama pakaian.

Visualisasi Ruang Laten: Melalui teknik PCA dan t-SNE, visualisasi menunjukkan bahwa model telah berhasil mengelompokkan berbagai kelas pakaian di ruang laten.








