# Chunky-Monkey
function chunk(arr, size) {
  // 请把你的代码写在这里
  var narr;
  var colltion = [];
  for(i=size;i<arr.length+size;i+=size){
  narr = arr.slice(i-size,i);
  colltion.push(narr);  
  }
  return colltion;
}
