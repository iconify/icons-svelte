<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="oh-q7qtwz"/><rect class="j6swy051u"/><rect class="x099_zptd"/><path class="ypm87sb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:minimum-launcher" {...props}></Icon>
<style>
:global(.j6swy051u) {
  width: 16.586px;
  height: 16.586px;
  x: 25.914px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

:global(.oh-q7qtwz) {
  width: 16.586px;
  height: 16.586px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

:global(.x099_zptd) {
  width: 16.586px;
  height: 16.586px;
  x: 5.5px;
  y: 25.914px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

:global(.ypm87sb6b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.207 42.5V25.914m-8.293 8.293H42.5");
}

</style>
