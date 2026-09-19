<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m5gsysbtv"/><path class="hf4sidgsi"/><path class="xakk13b4p"/><circle class="edxhxihcr"/><path class="e8targ9on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:3d-model-viewer" {...props}></Icon>
<style>
:global(.e8targ9on) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.101 30.609l.979-.979m-3.429.979l-6.243 6.243l2.45 2.449l6.243-6.243v-2.449z");
}

:global(.edxhxihcr) {
  cx: 24.029px;
  cy: 23.681px;
  r: 8.413px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.hf4sidgsi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.38 37.78l11.65 6.72l.04-12.41l.02-8.04l-7.49-4.32l-10.31-5.96l-.06 20.46l3.04 1.76");
}

:global(.m5gsysbtv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m41.767 13.774l-.058 20.451L24.029 44.5l.058-20.451z");
}

:global(.xakk13b4p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m41.767 13.774l-17.68 10.275L6.291 13.775L23.971 3.5z");
}

</style>
