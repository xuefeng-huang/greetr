# greetr
JS library to show greeting in different languages
## Usage
```js
var g = G$('John', 'Doe');
$('#login').on('click', function(){
    g.greet().setLang('cn').greet(true).log().HTMLGreeting('#greeting', true)
});
```