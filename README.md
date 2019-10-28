#latihan 1
# Cara penggunaan Git
# Apa Itu Git ?
* Git adalah salah satu sistem pengontrol versi(Version Control System) pada proyek perangkat lunak yang diciptakan Linus Torvalds.
* Pengontrol versi bertugas memcatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri.
* Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.
# Instalasi Git
* Download **Git**, Buka website resminya Git [git-scm.com](https://git-scm.com "Teken terus mass enak banget").
* Kemudian unduh Git sesuai dengan arsitektur komputer kita.
![Untitle](https://user-images.githubusercontent.com/56942922/67623743-0ddbe680-f853-11e9-86ff-a482934f5c9b.png)
* Selamat, Git sudah terinstal di windows. Untuk mencobanya,silahkan buka **CMD** atau **PowerShel**,kemudian ketik perintah
```git --version.```

![Untitled11](https://user-images.githubusercontent.com/56942922/67683986-eefd6180-f9c4-11e9-89f4-9bdc1306098d.png)
# Menambahkan Global Config
* Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi
user.name dan user.email
* konfigurasi ini bisa dilakukan untuk global repostiry atau individual
repository.
* apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi
kegagalan saat menjalankan perintah ```git commit```
* Config Global Repository

``$ git config --global user.name "nama_user"``

``$ git config --global user.email "nama_user"``
![Untitl](https://user-images.githubusercontent.com/56942922/67687891-8cf42a80-f9cb-11e9-9df8-7dfcf652d0a0.png)
# Perintah Dasar Git
* ``git init``, perintah untuk membuat repository local
* ``git add``, perintah untuk menambahkan file baru, atau perubahan pada file
pada staging sebelum proses commit. 
* ``git commit``, perintah untuk menyimpan perubahan kedalam database git. 
* ``git push`` -u origin master, perintah untuk mengirim perubahan pada
repository local menuju server repository. 
* ``git clone [url]``, perintah untuk membuat working directory yang diambil dari
repositry sever. 
* ``git remote add origin [url]``, perintah untuk menambahkan remote
server/reopsitory server pada local repositry (working directory)
* ``git pull``, perintah untuk mengambil/mendownload perubahan terbaru dari
server repository ke local repository
# Membuat Reposiory Local
* Buka direktory aktif, misal: ``d:\labs_pemrograman1`` (bukamenggunakan Windows Explorer)
* klik kanan pada direktory aktif tersebut, dan pilih menu ``Git Bash``,sehingga muncul git *bash commad*
* Buat direktory project praktikum pertama dengan nama **latihan1**
![Unti](https://user-images.githubusercontent.com/56942922/67690152-fd507b00-f9ce-11e9-9702-0a3b1af464eb.png)
* Sehingga terbentuk satu direktori baru dibawahnya, selanjutnyamasuk kedalam direktori tersebut dengan perintah cd *(changedirectory)*
* direktory aktif menjadi: ``d:\labs_pemrograman1\latihan1``
# Membuat Reposiory Local
* Jalankan perintah git init, untuk membuat repository local. 
* Repository baru berhasil di inisialisasi, dengan terbentuknya satudirektori hidden dengan nama **.git**
* Pada direktori tersebut, semua perubahan pada *working directory* akan disimpan.
![git init](https://user-images.githubusercontent.com/56942922/67690640-d181c500-f9cf-11e9-98b4-8b27d880549a.png)
# Menambahkan File baru pada repository
* Untuk membuat file dapat menggunakan text editor, lalu menyimpafilenya pada direktori aktif (repository)
* disini kita akan coba buat satu file bernama README.md (text file)
``$ echo “#Latihan 1” >> README.md``
* File ``README.md`` berhasil dibuat.
![echo](https://user-images.githubusercontent.com/56942922/67691370-0b9f9680-f9d1-11e9-93e4-5d804d075769.png)


