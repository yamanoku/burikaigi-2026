<template>
  <button type="submit">送信する</button>
　<button type="submit" disabled>送信する</button>
</template>

<style scoped>
button {
  padding: 10px 18px;
  background-color: #007bff;
  color: white;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  width: 300px;
}
button:disabled {
  background-color: #ccc;
  cursor: not-allowed;
}
</style>