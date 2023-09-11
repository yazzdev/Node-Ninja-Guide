# Web Developer (Pengantar)

Sebelum membahas tentang Back-end developer, kita perlu sungkem dulu nih sama yang namanya web development! 

*“Wah, siapa tuh?”*

> Web development adalah proses pembuatan website, dan mereka yang menggarapnya disebut web developer. Terdapat dua peran utama dalam web development yaitu: *front-end dan back-end.*

*"Gimana tuh maksudnya bang Messi?"*

*Jadi~* **Front-end** melakukan **request** ke **Back-end**, biasanya menggunakan protokol **HTTP**. Setelah Back-end menerima
**request** dari Front-end, maka **Back-end akan melakukan** apa yang diminta oleh **Front-end** dan memberi jawaban ke Front-end berupa **response.**

Nah, daftar permintaan dari Front-end ini akan dicatat di tempat yang bernama **server Back-end.**

*bisa kita simpulkan bahwa~*

- **Front-end** adalah bagian dari website yang berfokus pada tampilan dan mempermudah kita dalam melakukan request ke back end.
- Sementara **Back-end** adalah bagian dari website yang berfokus pada penyajian data untuk disampaikan pada Front-end.

Dengan kerja sama antara front-end dan back-end developer, website dapat berfungsi dengan baik dan memberikan pengalaman yang hebat kepada pengguna.

## Kita akan membahas beberapa hal, yaitu:
- Konsep Back-End
- Skill Back-End Developer
- Tools yang Digunakan oleh Back-End Developer
- Terminal


## Apa aja sih tugas Back End?
- **Perancangan Database yang Andal:** Membuat desain database yang handal dan dapat diuji untuk memastikan ketahanan data.
- **Desain API yang Sesuai:** Mendesain API sesuai dengan kebutuhan Front-End dan desain produk (Product Design).
- **Pengembangan Web API:** Membangun Web API (Back-End) yang bertanggung jawab atas penyimpanan dan pengelolaan data.
- **Implementasi Keamanan Data:** Menerapkan langkah-langkah keamanan dalam pengiriman dan pengelolaan data dari API yang dibuat, untuk melindungi data sensitif dan mencegah ancaman keamanan.

*Untuk front end akan dibahas di course tersendiri, yaa~*

## Skill wajib buat calon back end developer~
- Menguasai setidaknya satu bahasa pemrograman untuk membuat Web API seperti Ruby, Python, Node.js, atau PHP.
- Menguasai DBMS (SQL maupun Non-SQL).
- Mampu membuat desain database.
- Pengetahuan terkait security data & best practice.
- Memiliki pemahaman terhadap konsep client server & arsitekturnya.
- Mampu membuat API dengan ataupun tanpa menggunakan framework.
- Test Driven Development.

> Nah, dari skill set tadi disini ada beberapa stack (kumpulan teknologi) yang bisa kita jadikan acuan buat dipelajari supaya proses pembelajaran kedepannya nya semakin lebih mudah (pilih salah satu kalau baru belajar awal, setelahnya boleh eksplor yang lain ya!)

Biar lebih fokus, kita bakal belajar 3 stack ini aja ya sob!
- Node.js
- SQL (Backend)
- Express (Backend)

*Selain itu, kita juga bakal belajar tentang testing aplikasi
(unit test) beserta deployment-nya~*

Sebelum kita bahas tentang terminal, kita akan belajar dulu nih tentang Shell.

## “Shell itu apa, ya?”
**Shell adalah sebuah program yang memungkin kamu buat berinteraksi dengan sistem operasi yang kamu pakai.**

### Shell itu ada macam - macam, lho!
**Nah, berikut ini adalah daftar shell yang paling banyak digunakan:**
- bash
- zsh
- sh
- ash
- fish
- dll

*Khusus untuk materi ini, kita cuma bahas bash aja ya, sob!*

### “Bash? Apaan tuh?”
Sebagai salah satu **tool scripting populer pada Unix, Bash** sangat **berguna bagi para user Linux atau SysAdmin.** Nama Bash sendiri merupakan **akronim dari Bourne Again Shell.**

Bash script merupakan komponen yang sangat berpengaruh dan berguna bagi **pengembangan web.** *Script ini bakal mempersingkat task yang berulang ke satu line function call.*

Dengan demikian, **command yang panjang bakal dilebur menjadi satu kode yang mudah dijalankan.** Kalau biasanya kamu harus menjalankan command terminal satu persatu secara berulang-ulang, dengan bash kita bisa panggil bash-nya aja kayak contoh di
bawah~

```bash
function functionName {
first command
second command }
```

Oke, kita udah tahu apa itu shell dan jenis-jenis shell.

Sekarang, kita bakal berkenalan dengan Terminal~

## Terminal dalam server
**Terminal** adalah *aplikasi yang menjalankan shell* tadi. Jadi buat bisa menjalankan shell kita harus punya terminal. Terminal berguna banget dalam dunia pemrograman karena nggak semua aplikasi yang kita pakai bakal ada GUI-nya (Graphical User Interface).

### Berikut adalah daftar hal - hal apa saja yang bisa kamu lakukan di terminal, gengs!
- Berpindah dari satu directory ke directory lain.
- Menghapus file atau directory.
- Mengganti nama file atau directory.
- Copy & Paste file atau directory.
- Memindahkan sebuah file atau directory.
- Menampilkan daftar file atau directory.

Pas pakai terminal, anggap aja terminal tersebut adalah file manager kamu. Di dalam terminal juga ada yang namanya **sistem Path.**

*Tapi, apa itu Path?*

Path adalah teks yang menunjukan lokasi suatu file atau directory dalam komputer kita. Contoh path dari directory home sendiri adalah **home/userkamu.**

**Dari shell sendiri udah menyediakan perintah-perintah buat melakukan hal-hal menarik. Berikut ini adalah beberapa daftarnya:**
- **cd :** Untuk berpindah directory
- **mv :** Untuk mengganti nama file atau directory, bisa juga untuk memindahkan file atau directory
- **touch :** Untuk membuat sebuah file
- **mkdir :** Untuk membuat sebuah directory
- **cp :** Untuk copy file
- **rm :** Untuk menghapus file
- **rmdir :** Untuk menghapus directory

Pas melakukan software development, dianjurkan banget buat pakai IDE, sob. Nggak mungkin dong kamu cuma berbekal notepad++ aja, karena notepad++ belum dilengkapi fitur buat compile atau running kode. IDE di dalam software development sendiri biasa terdiri dari beberapa hal, antara lain:
- Text editor, untuk melakukan coding.
- Terminal, untuk menjalankan coding dan operasi file.

Berikut contoh-contoh text editor yang populer dipakai:
- Visual Studio Code
- Atom
- Sublime Text
- Eclipse (Java and Kotlin only)
- Vim

Setiap editor punya kelebihan masing-masing.Tapi buat pemula, dianjurkan buat pakai **Visual StudioCode aja,** ya.

*“Lho, kenapa?”*

**Karena editor tersebut punya beberapa keunggulan,
antara lain:**
- Mempunyai integrasi secara langsung dengan Terminal (Integrated Terminal).
- Mempunyai banyak opsi plugin yang bisa kita pakai buat mempermudah proses development dari segi penulisan kode.
- Mempunyai suggestion dan auto-completion, menghindari kesalahan dalam menulis kode (typo dan lain-lain).
- Mempunyai linter, dimana bisa berguna dalam mendeteksi kira-kira di mana letak kesalahan kode.

[Kamu bisa download Visual Studio Code di sini!](https://code.visualstudio.com/download)

[Sebelum memulai ngoding, silahkan download dulu Node.js di OS masing-masing ya~](https://nodejs.org/en/download)

Cara cek instalasi yang udah dilakukan kamu bisa melakukan proses dibawah ini ya!
1. Buka terminal / cmd
2. Jalankan node -v

## Ada Latihan nih buat kamu~
Buatlah struktur folder sesuai dengan ketentuan berikut hanya dengan menggunakan command line/terminal.

```
> LATIHAN
  > rest-api
    > controllers
        auth.js
    > model
        user.js
    > routes
        index.js
    > view
    main.js
```