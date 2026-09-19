<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="xy10iobvo"/><rect class="wyu98x7zp"/><path class="i_1ax38ib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:cod-warzone" {...props}></Icon>
<style>
:global(.i_1ax38ib) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.329 22.773v-8.597h2.814c1.591 0 2.881 1.292 2.881 2.887s-1.29 2.887-2.88 2.887h-2.815m2.814 0l2.814 2.82m-13.384-8.594l-2.149 8.597l-2.15-8.597l-2.149 8.597l-2.149-8.597m13.349 5.749h-3.809m-.943 2.848l2.848-8.598l2.847 8.598");
}

:global(.i9clfwm2k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

:global(.wyu98x7zp) {
  width: 5.696px;
  height: 8.597px;
  x: 17.45px;
  y: 25.227px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.848px;
  ry: 2.848px;
}

:global(.xy10iobvo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.371 33.825v-8.598l5.696 8.598v-8.598m-20.567 0h5.696L10.5 33.825h5.696m17.005-4.299h2.803m1.496 4.299h-4.299v-8.598H37.5");
}

</style>
