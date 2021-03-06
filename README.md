# ImageWorld
My solution for task of "Yandex school of mobile development"

### Getting started
This application is made for admission to the school of Yandex mobile development. This test application loads photos from [pixabay](http://pixabay.com/) and show as gallery.  
You can download built apk file from this link: [link](https://yadi.sk/d/Sf11wY7c3VSQRw).  
Demonstration gif (10.4 MB): [gif](/screenshots/demonstration.gif).

### Features
* Search images by keyword (russian, english)
* Sort by latest or popular
* Supports swipe-to-next-previous, zoom and other gestures
* Pagination images
* Supports horizontal orientation
* Caching images
* Sharing to other applications
* Download to storage
* Some unit tests

### Task (russian):

> Необходимо создать приложение для Android на языке Java или Kotlin, обладающее следующей минимальной функциональностью:
>
> * На стартовом экране отображается лента картинок, разделённая на несколько столбцов. Есть возможность прокрутки.
> * По нажатию на картинку она открывается в новом окне, во весь экран.
> * Ленту картинок приложение получает по сети из любого открытого источника (например, через API Яндекс.Диска).
>
> Будет нелишним уделить внимание:
>
> * отсутствию падений и непредусмотренного поведения приложения при выполнении базовых действий;
> * понятности интерфейса – чтобы перед использованием приложения не приходилось читать инструкции;
> * общей плавности и отзывчивости интерфейса;
> * комментариям в коде;
> * обработке ошибок;
> * кэшированию (например, можно научить приложение сохранять предыдущий ответ сервера);
> * тестам.

### Screenshots
![Main portrait mode](/screenshots/main_portrait.jpeg?raw=true "Main portrait mode")
![Internet error](/screenshots/internet_error.jpeg?raw=true "Internet error")
![Sort by](/screenshots/sort_type.jpeg?raw=true "Sort by")
![Search](/screenshots/search.jpeg?raw=true "Search")
![Full view portrait](/screenshots/full_portrait.jpeg?raw=true "Full view portrait")
![Full view zooming](/screenshots/full_zooming.jpeg?raw=true "Full view zooming")
![Full view downloaded](/screenshots/downloaded.jpeg?raw=true "Full view downloaded")
![Full view sharing](/screenshots/sharing.jpeg?raw=true "Full view sharing")
![Main landscape mode](/screenshots/main_landscape.jpeg?raw=true "Main landscape mode")
![Full view landscape](/screenshots/full_landscape.jpeg?raw=true "Full view landscape")


### Used libraries
* [Android Architecture Components](https://github.com/googlesamples/android-architecture-components)
* [ButterKnife](https://github.com/JakeWharton/butterknife)
* [Glide](https://github.com/bumptech/glide)
* [Fast android networking](https://github.com/amitshekhariitbhu/Fast-Android-Networking)
* [Robolectric](https://github.com/robolectric/robolectric)
