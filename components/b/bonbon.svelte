<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><rect class="tioc7mbwb"/><path class="zcjeq9b9z"/><rect class="dfhoazn7a"/><path class="k30cq3qdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:bonbon" {...props}></Icon>
<style>
:global(.dfhoazn7a) {
  width: 5.406px;
  height: 7.163px;
  x: 21.308px;
  y: 27.837px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.703px;
  ry: 2.703px;
}

:global(.i9clfwm2k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

:global(.k30cq3qdc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.343 35v-4.46a2.703 2.703 0 1 1 5.406 0V35m-21.498-4.46a2.703 2.703 0 1 1 5.406 0v1.757a2.703 2.703 0 1 1-5.406 0m0 0v-8.109");
}

:global(.tioc7mbwb) {
  width: 5.406px;
  height: 7.163px;
  x: 21.308px;
  y: 14.649px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.703px;
  ry: 2.703px;
}

:global(.zcjeq9b9z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.343 21.812v-4.46a2.703 2.703 0 1 1 5.406 0v4.46m-21.498-4.46a2.703 2.703 0 1 1 5.406 0v1.757a2.703 2.703 0 1 1-5.406 0m0 0V11");
}

</style>
