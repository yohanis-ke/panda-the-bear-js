1. var img = document.querySelector('img'); img.src = img.src = 'https://www.zoo-berlin.de/fileadmin/_processed_/4/4/csm_Meng_Meng_Baby_1_88cad0f74f.jpg';

2. var title = document.querySelector('h1') title.innerText = 'Yohanis Ayano'

3. var employment = document.querySelector('#employment h3') employment = 'student'

4. document.body.style.backgroundColor = 'CornflowerBlue '

5. highlight.forEach(function(element) {element.style.background = 'DarkSlateGray ' })

6. var h1 = document.querySelector('h1'); h1.style.fontFamily = 'Courier'

7. var button = document.querySelector('.action-icon-bg'); button.style.backgroundColor = 'black'

8. var placeholder = document.querySelector('#name'); placeholder.placeholder = 'Find your self';

9. var placeholder = document.querySelector('#message'); placeholder.placeholder = 'state your business';

10. var placehheyoooheyoooolder = document.querySelector('#name'); placeholder.value = 'your name is';

11. var placeholder = document.querySelector('#submit'); placeholder.value = 'send it';

12. var emailPlaceholder = document.querySelector('#email'); emailPlaceholder.placeholder = "koalathebear@gmail.com";

13. var button = document.querySelector('#submit'); button.disabled = true;

14. var parent = document.querySelector('aside'); var bio = document.querySelector('.bio-info'); parent.removeChild(bio);

===================PART 2================
Removing Elements from the DOM
------------------------------
1. var time = document.querySelector('#time-travel'); time.parentElement.parentElement.removeChild(time.parentElement);

Adding Elements to the DOM
------------------------------
1. var pikachu = document.querySelector('[title="Pikachu"]');
var portfolio = document.querySelector('.portfolio-container'); portfolio.appendChild(pikachu);

2. for (x = 0; x < 10; x++) {portfolio.insertAdjacentHTML('beforeend', pikachu)}
