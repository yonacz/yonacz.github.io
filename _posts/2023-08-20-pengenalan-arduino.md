---
title: "Pengenalan Arduino"
excerpt: "Arduino adalah microcontroller, dan microcontroller secara singkat adalah, “Sebuah sistem komputer yang fungsional dalam sebuah chip"
author_profile: false
sidebar:
  title: "Belajar Arduino"
  nav: sidebar-arduino
categories:
  - Arduino
tags:
  - arduino
  - avr
  - microcontroller
  - atmega
header:
  image: /assets/images/header-web.png
toc: true
toc_label: "Pengenalan Arduino"
toc_icon: "list-alt"
toc_sticky: true

---

# Apa Itu Arduino?

Arduino adalah Microcontroller yang menggunakan chip AVR dari ATMEL, yang sering digunakan adalah keturunan ATMEGA.

Arduino adalah microcontroller, dan microcontroller secara singkat adalah, “Sebuah sistem komputer yang fungsional dalam sebuah chip”. Didalamnya sudah terdapat processor, memory, input, output, dan bisa dibilang bahwa microcontroller ini adalah komputer dalam versi mini (chip).

Karena ukurannya yang kecil, microcontroller sering digunakan untuk mengendalikan rangkaian lampu LED, membuat MP3 Player, DVD, dan untuk membuat sebuah projek yang kita butuhkan seperti alarm motor misalnya. Dan tentu saja bisa juga untuk membuat project robot. Dan dalam robot sendiri kita sudah ketahui bahwa microcontroller, berfungsi sebagai otaknya.

<figure style="width: 300px" class="align-right">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/2023-08-20-arduino-board.png" alt="">
</figure>

Lantas, apa yang membedakan Arduino dengan microcontroller yang lain? Arduino bersifat open source, skemanya dapat di cloning tersedia bebas di website-nya arduino. Terus Arduino memiliki bahasa peograman sendiri. Didalam chipnya sudah ada bootloader, dimana bahasa pemogramannya menggunakan bahasa C, tapi yang sudah disederhanakan. Dan juga sudah tersedia berbagai macam library.

Dan yang paling penting yaitu Arduino adalah Microcontroller yang paling populer di Dunia. Dan karena open source, pengembangnya ada dimana-mana, sehingga kita juga tidak akan kesulitan ketika mau mencari referensi.

# Sejarah Singkat Lahirnya Arduino

Arduino berawal dari sebuah tesis yang dibuat oleh Hernando Barragan, di Institute Ivrea, Italia pada tahun 2005, dikembangkan oleh Massimo Banzi dan David Cuartielles dan diberi nama Arduin of Ivrea. Lalu diganti nama menjadi Arduino yang dalam bahasa Italia berarti teman yang berani.

Tujuan awal dibuatnya Arduino adalah untuk membuat perangkat yang mudah dan murah, dari perangkat yang ada pada saat itu. Dan perangkat tersebut ditujukan untuk para siswa yang akan membuat perangkat desain dan interaksi.

<figure style="width: 300px" class="align-right">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/2023-08-20-arduino-team.jpg" alt="team arduino">
</figure>

Saat ini tim pengembangnya adalah Massimo Banzi, David Cuartielles, Tom Igoe, Gianluca Martino, David Mellis, dan Nicholas Zambetti. Mereka mengupayakan 4 hal dalam Arduino ini, yaitu:
1.  Harga terjangkau
2.  Dapat dijalankan diberbagai sistem operasi, Windows, Linux, Max, dan sebagainya.
3.  Sederhana, dengan bahasa pemograman yang mudah bisa dipelajari orang awam, bukan untuk orang teknik saja.
4.  Open Source, hardware maupun software.

Sifat Arduino yang Open Source, membuat Arduino berkembang sangat cepat. Dan banyak lahir perangkat-perangkat sejenis Arduino, Seperti DFRDuino, SPDUINO atau Freeduino.

Sampai saat ini pihak resmi, sudah membuat berbagai jenis-jenis Arduino… Mulai dari yang paling mudah dicari dan paling banyak digunakan, yaitu Arduino Uno. Hingga Arduino yang sudah menggunakan ARM Cortex, beebentuk Mini PC. Dan Arduino juga sudah banyak dipaka oleh perusahaan besar. Contohnya Google menggunakan Arduino untuk Accessory Development Kit, NASA memakai Arduino untuk prototypin, ada lagi Large Hadron Colider memakai Arduino dalam beberapa hal untuk pengumpulan data.

# Alasan Mengapa Harus Pilih Arduino?

1.  **Karena Arduino Mempunyai Bootloader.** Bootloader semacam sistem tersendiri untuk Arduino, yang membuat Arduino tidak memerlukan lagi tambahan chip programmer. Bootloader ini berfungsi untuk menangani proses memasukan program dari komputer ke Arduino.
2.  **Karena Arduino Terjangkau.** Coba cek harganya di marketplace ada banyak boards arduino yang harganya murah murah paling sekitar 100 ribuan, malah bisa kurang dari itu dan fungsinya masih sama gak beda jauh.
3.  **Karena Arduino Mudah Dipelajari.** Bahasa pemograman Arduino adalah bahasa C yang sudah menjadi sederhana. Sehingga memudahkan pemula. Kamu pun yang bukan orang teknik atau berasal dari programmer, pasti bisa menggunakan Arduino.
4.  **Karena Arduino Menggunakan USB.** Untuk pemograman sudah tidak memerlukan paralel port atau sebagainya, USB memudahkan kamu untuk proses pemograman. Karena USB ada di semua perangkan komputer.
5.  **Karena Arduino Memiliki Banyak Library Gratis.** Library ini berfungsi untuk menyingkat pemograman, sehingga kamu nggak perlu pusing lagi. Dan tersedia berbagai macam, ada yang untuk LCD, Servo, Sensor, dan sebagainya. 
6.  **Karena Arduino Memiliki Fasilitas Lengkap.** Sudah tersedia memori, pin input output yang lengkap. Ada PWMnya juga, ADC, timer, dan sebagainya.
7.  **Karena Arduino Open Source.** Tidak hanya secara software saja yang bisa kamu utak-atik, tapi juga secara hardware. Kamu bahkan bisa membuat Arduino buatan kamu sendiri, dan malah pihak Arduino sendiri juga memberikan skemanya (arduino.cc). Dan karena Open Source juga, Arduino menjadi berkembang sangat cepat diseluruh dunia.
8.  **Karena Komunitas Arduino Banyak.** Komunitas-komunitas ini membuat kamu tidak pusing saat mau bertanya, atau mencari referensi untuk belajar. Di Google dan youtube pun, banyak contoh-contoh projek Arduino yang telah dibuat.

# Jenis-Jenis board Arduino

## Arduino Uno

<figure style="width: 300px" class="align-right">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/2023-08-20-arduino-uno.jpg" alt="arduino uno">
</figure>

Arduino menganggap Uno sebagai produk entry-level. Namun, pada kenyataannya Uno adalah konfigurasi Arduino yang paling populer di dunia. Sepak terjangnya sangat familier bagi siapa saja yang telah menggunakan Arduino. Selain itu, sebagian besar Arduino shield di desain agar sesuai dengan Arduino Uno.
Arduino Uno sering digunakan sebagai prototyping board, yang pada akhirnya akan menjadi produk akhir berdasarkan Arduino atau yang lebih kecil, masih di seputaran chip mikrokontroler ATMega328. Chip ini merupakan perangkat yang menjadi dasar Arduino Uno. 

Uno memiliki 14 pin I/O digital, 6 di antaranya mampu menghasilkan Pulse Width Modulator (PWM). Selain itu, Uno juga memiliki 6 pin input analog. Arduino Uno board berisi 32 KB memori flash untuk menyimpan program, setengah kilobyte digunakan oleh boot loader dan RAM statis 2 KB di Uno. ATMega328 memiliki clock 16 megahertz, untuk skema lengkap serta tata letak board sirkuit untuk Uno anda dapat melihatnya pada situs resmi Arduino.

Arduino Uno dapat dihidupkan secara langsung melalui port USB yang juga digunakan untuk berkomunikasi dengan komputer. Selain itu, Anda pun dapat menggunakan adaptor 7-12 volt. Sebenarnya, regulator tegangan bawaan Uno mampu menangani tegangan hingga 20 volt, namun pada tegangan yang lebih tinggi akan ada banyak energi panas terhamburkan sehingga ada sedikit energi terbuang. Sedangkan pada pin I/O digital dapat memasok arus hingga 20 miliampere DC.

Kloningan Uno dan official Uno sendiri tersedia dalam sejumlah konfigurasi berbeda. Pada beberapa perangkat, ATMega328 di simpan di dalam soket yang dapat di lepas, sehingga memungkinkan untuk di gunakan pada perangkat lain. Sedangkan ada juga konfigurasi Uno lain yang memiliki versi fixed, di mana chip ini tersolder langsung kepada board.

Jika Anda ingin mulai mempelajari Arduino, saya rekomendasikan untuk menggunakan Arduino Uno atau kloningannya, ini adalah cara termurah dan bagus untuk memasuki dunia mikrokontroler Arduino yang menyenangkan.


### Ordered Lists

1. Item one
   1. sub item one
   2. sub item two
   3. sub item three
2. Item two

### Unordered Lists

* Item one
* Item two
* Item three

Welcome to image alignment! The best way to demonstrate the ebb and flow of the various image positioning options is to nestle them snuggly among an ocean of words. Grab a paddle and let's get started.

![image-center]({{ site.url }}{{ site.baseurl }}/assets/images/image-alignment-580x300.jpg){: .align-center}

The image above happens to be **centered**.

![image-left]({{ site.url }}{{ site.baseurl }}/assets/images/image-alignment-150x150.jpg){: .align-left} The rest of this paragraph is filler for the sake of seeing the text wrap around the 150×150 image, which is **left aligned**.

As you can see there should be some space above, below, and to the right of the image. The text should not be creeping on the image. Creeping is just not right. Images need breathing room too. Let them speak like you words. Let them do their jobs without any hassle from the text. In about one more sentence here, we'll see that the text moves from the right of the image down below the image in seamless transition. Again, letting the do it's thing. Mission accomplished!

And now for a **massively large image**. It also has **no alignment**.

![no-alignment]({{ site.url }}{{ site.baseurl }}/assets/images/image-alignment-1200x4002.jpg)

The image above, though 1200px wide, should not overflow the content area. It should remain contained with no visible disruption to the flow of content.

![image-right]({{ site.url }}{{ site.baseurl }}/assets/images/image-alignment-300x200.jpg){: .align-right}

And now we're going to shift things to the **right align**. Again, there should be plenty of room above, below, and to the left of the image. Just look at him there --- Hey guy! Way to rock that right side. I don't care what the left aligned image says, you look great. Don't let anyone else tell you differently.

In just a bit here, you should see the text start to wrap below the right aligned image and settle in nicely. There should still be plenty of room and everything should be sitting pretty. Yeah --- Just like that. It never felt so good to be right.

And just when you thought we were done, we're going to do them all over again with captions!

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/image-alignment-580x300.jpg" alt="">
  <figcaption>Look at 580 x 300 getting some love.</figcaption>
</figure> 

The figure above happens to be **centered**. The caption also has a link in it, just to see if it does anything funky.

<figure style="width: 150px" class="align-left">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/image-alignment-150x150.jpg" alt="">
  <figcaption>Itty-bitty caption.</figcaption>
</figure> 

The rest of this paragraph is filler for the sake of seeing the text wrap around the 150×150 image, which is **left aligned**.

As you can see there should be some space above, below, and to the right of the image. The text should not be creeping on the image. Creeping is just not right. Images need breathing room too. Let them speak like you words. Let them do their jobs without any hassle from the text. In about one more sentence here, we'll see that the text moves from the right of the image down below the image in seamless transition. Again, letting the do it's thing. Mission accomplished!

And now for a **massively large image**. It also has **no alignment**.

<figure style="width: 1200px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/image-alignment-1200x4002.jpg" alt="">
  <figcaption>Massive image comment for your eyeballs.</figcaption>
</figure> 

The figure element above has an inline style of `width: 1200px` set which should break it outside of the normal content flow.

<figure style="width: 300px" class="align-right">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/image-alignment-300x200.jpg" alt="">
  <figcaption>Feels good to be right all the time.</figcaption>
</figure> 

And now we're going to shift things to the **right align**. Again, there should be plenty of room above, below, and to the left of the image. Just look at him there --- Hey guy! Way to rock that right side. I don't care what the left aligned image says, you look great. Don't let anyone else tell you differently.

In just a bit here, you should see the text start to wrap below the right aligned image and settle in nicely. There should still be plenty of room and everything should be sitting pretty. Yeah --- Just like that. It never felt so good to be right.

And that's a wrap, yo! You survived the tumultuous waters of alignment. Image alignment achievement unlocked!
