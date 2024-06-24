// * parseInt virgülden sonrasından kurtulur

var a = 5.9
console.log(parseInt(a))

// * Değişkenin sayı olup olmadığını kontrol etmek için isNaN ı kullanırız, sayı değilse true cevabını verecektir.

var a = "test"
a = parseInt(a) 
console.log(isNaN(a))

// isFinite değişkenimizin sonlu mu sonsuz mu oldugunu acıklar

var a = 3
console.log(isFinite(a))


// Virgülden sonra kaç değişken olduğunu öğrenmek için toFixed ı kullanırız

var a = 32.873271883
console.log(a.toFixed(2))


------string

// number sayı
// null boş
// symbol unique
// boolean true false 1/0
// undefined
// BigInt sayı


var ozgur = 1 
ozgur = 3
ozgur = 22
console.log(ozgur)

//string

var ozgur = "DENEME"
console.log(ozgur)

//boolean
ozgur = true
console.log(ozgur)


//BigInt
ozgur = 2n
console.log(10n * 21n)

//symbol
ozgur = Symbol("denemesymbol")
console.log(ozgur)


// null
ozgur = null
console.log(ozgur)

var ozzgur

ozzgur = "deneme2"
console.log(ozzgur)

//
// 
//

var a = "deneme"
console.log(a)

// Alt gr + , (2)  -> bununla kodun içine kod yazabilirsin

var deneme1 = ` ${ozgur} ${ozzgur} ${3 + 5}`


//stringlerin belirli bir parçasını alma
var b = "ozgur"
console.log(b[2])

// yukarıda b nin yanına yazdıgımız sayı var b karsılıgı olan ozgur un kacıncı herfini almak istediğimizi gösterir.


//-------------------------------//--------------------------//-----------------------//


// belli bir karakterin indexini bulmak için a.indexOf(x) kullanırız bknz:

var ozgur = "Ne mutlu türküm diyene"
console.log(a.indexOf("r"))


// KONTROL
console.log(a.startsWith("N"))

//icerip icermeme kontrolü
console.log(a.includes("Tü"))


console.log(a.includes("de"))
//t=0 ü=1 r=2 K=3 i=4 y=5 e=6


//stingi parçalama

var d ="nemutlutürkümdiyene"
console.log(a.slice(1, 3))

// hepsini büyük harfe çevirme
console.log(a.toUpperCase())

// hepsini küçük harfe çevirme
console.log(a.toLowerCase())

// stringin uzunluğunu öğrenmeÜ
console.log(a.length)
