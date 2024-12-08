# Sistem Rekomendasi Tempat Wisata Toba

Proyek ini bertujuan untuk membangun sistem rekomendasi untuk tempat wisata di kawasan Danau Toba menggunakan beberapa teknik machine learning , yaitu Collaborative Filtering (CF) dengan GNN (Graph Neural Network) , Content-Based Filtering (CBF) dengan Alternating Least Squares (ALS) , dan Proposed Model yaitu  menggunakan Deep Learning

## Deskripsi Proyek

Proyek ini menggunakan dataset yang berisi informasi tempat wisata di kawasan Danau Toba. Tujuan utama proyek ini adalah untuk memberikan rekomendasi tempat wisata kepada pengguna berdasarkan preferensi mereka, baik dengan menggunakan data interaksi pengguna (Collaborative Filtering) atau deskripsi tempat wisata (Content-Based Filtering), serta meningkatkan akurasi dengan Graph Neural Network.

### Model yang Digunakan:
1.**Graph Neural Network (GNN)**  
   Model ini menggunakan Graph Neural Network untuk menggali hubungan kompleks antar tempat wisata dan pengguna dalam bentuk graf. Pendekatan ini diusulkan untuk meningkatkan kualitas rekomendasi dengan menangkap keterkaitan antar entitas di dalam jaringan.

2. **Alternating Least Squares (ALS**)
   model ini merupakan   algoritma yang sering digunakan dalam sistem rekomendasi, khususnya untuk faktorisasi matriks. ALS sangat berguna dalam menangani data matriks yang jarang (sparse data) seperti data rating pengguna pada item

3.  **Deep Learning**  
   Model ini menggunakan teknik pembelajaran mesin berbasis interaksi pengguna (ratings atau behavior) untuk memprediksi rekomendasi yang relevan. Deep Learning digunakan untuk meningkatkan kemampuan model dalam menangkap pola-pola kompleks pada data pengguna dan tempat wisata.



