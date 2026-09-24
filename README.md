Website Profil Kelas XI RPL
Anggota:  Areeqah
          Arief
          Septi
          Nessa

          Refleksi Tim:
Sebelum menggunakan GitHub Issues:Pembagian tugas dan pelacakan bug atau fitur masih dilakukan secara manual (misalnya lewat chat grup), sehingga terkadang ada tugas yang terlewat atau tumpang tindih antar anggota tim.

Setelah menggunakan GitHub Issues:
Pengelolaan tugas menjadi jauh lebih terstruktur dan transparan karena setiap pekerjaan, perbaikan halaman web (kontak.html, profil.html), dan target fitur tercatat dengan jelas beserta penanggung jawabnya.   

Hal yang paling membantu:
Fitur pelacakan tugas, penggunaan struktur branching yang terpisah per fitur (seperti feature/home dan feature/profil), serta alur kerja Pull Request dan Code Review yang memudahkan penggabungan kode bersama.   

Hal yang masih membingungkan:
Sempat menghadapi kendala teknis konfigurasi hak akses Git (error 403) serta penyesuaian alur kerja awal saat menyinkronkan branch lokal ke remote repository.

Perbaikan workflow tim:
Lebih membiasakan komunikasi yang intens sebelum melakukan merge kode ke branch utama, memastikan penamaan file dan aset lokal sudah konsisten agar tidak ada error saat di-deploy, serta disiplin menggunakan branch dan commit message yang deskriptif.  

          Simulasi masalah
Kasus 1

Jawaban: Andi dan Budi seharusnya melakukan koordinasi pembagian tugas menggunakan branch terpisah (misalnya Andi di branch feature/profil-biodata dan Budi di branch feature/profil-visi) atau membagi bagian kodingan secara modular agar tidak terjadi merge conflict pada file yang sama secara bersamaan.

Kasus 2

Apakah Issue sebaiknya langsung dianggap selesai? Tidak

Mengapa? Karena sebuah tugas (issue) baru bisa dianggap benar-benar selesai jika kodenya sudah dikirim (push), dibuatkan Pull Request, melalui proses Code Review, dan berhasil digabungkan (merged) ke branch utama tanpa ada error.

Kasus 3

Apakah otomatis Budi memiliki kontribusi lebih besar? Belum tentu

Jelaskan: Jumlah commit yang banyak tidak selalu mencerminkan kontribusi yang lebih besar, karena bisa jadi Budi melakukan banyak commit kecil untuk perubahan sepele, sementara Andi melakukan sedikit commit tetapi langsung mencakup fungsionalitas fitur yang besar dan kompleks.

Kasus 4

Bagaimana cara menilai kontribusinya? Penilaian kontribusi sebaiknya dilihat dari substansi atau dampak nyata dari kode yang diubah (substantive changes) seperti penambahan fitur dan penyelesaian masalah, bukan hanya dari jumlah frekuensi commit atau perubahan baris kosong/spasi semata.
