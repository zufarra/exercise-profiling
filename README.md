#Profiling Exercise

Screenshots:

1. /all-student:
   
- j-meter:

![image](https://github.com/user-attachments/assets/e323845a-7773-4ebb-8b79-3e70d5fd38e9)


- cmd:

![image](https://github.com/user-attachments/assets/0338ad08-b8ef-4e94-97ad-2484bd2298de)


2. /all-student-name:
   
- j-meter:

![image](https://github.com/user-attachments/assets/02928352-8341-4d56-bdd6-404fbc97425f)


- cmd:

![image](https://github.com/user-attachments/assets/ba39d627-72dd-4188-9673-90cc3e26dc98)


3. /highest-gpa:
   
- j-meter:

![image](https://github.com/user-attachments/assets/cb872f0a-55c0-4722-8137-802028eb1089)


- cmd:

![image](https://github.com/user-attachments/assets/d275ce79-60b4-45e6-b163-f3ba45295ace)

After Optimization:

1. /all-student

![image](https://github.com/user-attachments/assets/5e396c26-2a3f-49c8-bfab-677ef18060ca)


2. /all-student-name

![image](https://github.com/user-attachments/assets/ec737b33-4ca5-4869-8718-d81f58db8f7a)


3. /highest-gpa

![image](https://github.com/user-attachments/assets/d75e5358-3338-43f1-9ccd-fb1cd1d5b409)

Refleksi Tutorial Modul 5:

1. What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?

Jawab:

JMeter digunakan untuk menguji performa aplikasi dengan mensimulasikan beban pengguna, mengukur respons waktu, throughput, dan mengidentifikasi hambatan pada sistem atau jaringan. Sementara itu, IntelliJ Profiler berfokus pada analisis mendalam terhadap penggunaan CPU, memori, dan thread dalam kode untuk menemukan inefisiensi pada tingkat metode atau algoritma. Dengan kata lain, JMeter membantu mengevaluasi kinerja aplikasi dalam skala besar, sedangkan IntelliJ Profiler digunakan untuk mengoptimalkan efisiensi eksekusi kode secara internal.

2. How does the profiling process help you in identifying and understanding the weak points in your application?

Jawab:

Proses profiling membantu mengidentifikasi dan memahami titik lemah dalam aplikasi dengan menganalisis penggunaan CPU, memori, dan eksekusi thread secara mendetail. Profiling memungkinkan pengembang mendeteksi metode atau proses yang memakan sumber daya berlebihan, menemukan bottleneck, serta mengidentifikasi kebocoran memori atau performa yang tidak efisien. Dengan wawasan ini, pengembang dapat mengoptimalkan kode, meningkatkan efisiensi eksekusi, dan memastikan aplikasi berjalan lebih cepat serta stabil.

3. Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?

Jawab:

IntelliJ Profiler sangat efektif dalam menganalisis dan mengidentifikasi bottleneck dalam kode aplikasi. Dengan menyediakan visualisasi penggunaan CPU, memori, dan eksekusi thread secara real-time, profiler ini membantu pengembang menemukan proses yang tidak efisien, mendeteksi kebocoran memori, serta mengoptimalkan performa aplikasi. Kemampuannya dalam memberikan wawasan mendetail tentang eksekusi kode memungkinkan pengembang untuk memperbaiki dan meningkatkan efisiensi aplikasi dengan lebih cepat dan tepat.

4. What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?

Jawab:

Tantangan utama dalam pengujian performa dan profiling adalah mengidentifikasi bottleneck yang kompleks, menganalisis data dalam jumlah besar, serta memastikan hasil yang akurat dan relevan dengan kondisi produksi. Selain itu, perbedaan lingkungan pengujian dan produksi dapat memengaruhi validitas hasil. Untuk mengatasi tantangan ini, pendekatan yang digunakan meliputi simulasi beban yang realistis, penggunaan alat profiling yang tepat seperti IntelliJ Profiler, serta analisis data yang mendalam untuk menemukan akar permasalahan. Selain itu, melakukan iterasi pengujian dan optimasi secara berulang membantu memastikan performa aplikasi tetap optimal.

5. What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?

Jawab:

Menggunakan IntelliJ Profiler untuk profiling kode aplikasi memberikan berbagai manfaat, seperti identifikasi bottleneck secara akurat, analisis penggunaan CPU dan memori yang mendalam, serta deteksi kebocoran memori dan eksekusi thread yang tidak efisien. Dengan visualisasi data yang intuitif, pengembang dapat memahami performa aplikasi secara lebih jelas dan menemukan area yang perlu dioptimalkan. Selain itu, profiler ini memungkinkan debugging yang lebih efektif, sehingga proses pengembangan menjadi lebih efisien dan aplikasi dapat berjalan dengan lebih cepat serta stabil.

6. How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter?

Jawab:

Ketika hasil profiling dengan IntelliJ Profiler tidak sepenuhnya konsisten dengan temuan dari pengujian performa menggunakan JMeter, langkah pertama yang dilakukan adalah menganalisis perbedaan skenario pengujian, seperti jumlah beban, lingkungan eksekusi, dan konfigurasi sistem. Selanjutnya, dilakukan cross-check terhadap metrik yang dihasilkan oleh kedua alat untuk mengidentifikasi kemungkinan faktor yang memengaruhi perbedaan tersebut. Jika diperlukan, pengujian ulang dengan skenario yang lebih mendekati kondisi produksi dapat dilakukan untuk memastikan validitas hasil. Dengan pendekatan ini, analisis performa menjadi lebih akurat dan solusi optimasi dapat diterapkan secara lebih efektif.

7. What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?

Jawab:

Setelah menganalisis hasil pengujian performa dan profiling, strategi optimasi yang diterapkan meliputi refaktorisasi kode untuk meningkatkan efisiensi, mengoptimalkan penggunaan memori dan CPU, serta mengurangi kompleksitas algoritma yang tidak perlu. Selain itu, dilakukan caching, optimasi query database, dan pengelolaan thread yang lebih baik untuk meningkatkan respons aplikasi. Untuk memastikan perubahan tidak memengaruhi fungsionalitas, pengujian regresi dan unit testing dijalankan secara menyeluruh, serta dilakukan validasi sebelum perubahan diterapkan.







