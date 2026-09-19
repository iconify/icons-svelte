<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sdv4dtbvr"/><rect class="nnyaokllk"/><rect class="xqvksf5nu"/><path class="i9clfwm2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:100" {...props}></Icon>
<style>
:global(.i9clfwm2k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

:global(.nnyaokllk) {
  width: 7.287px;
  height: 11px;
  x: 18.17px;
  y: 18.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.644px;
  ry: 3.644px;
}

:global(.sdv4dtbvr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.083 19.997l2.75-1.497v11");
}

:global(.xqvksf5nu) {
  width: 7.287px;
  height: 11px;
  x: 28.629px;
  y: 18.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.644px;
  ry: 3.644px;
}

</style>
