<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qhgja6bzw"/><circle class="eai3f7b8u"/><path class="p77bwrbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:bluetooth-scanner" {...props}></Icon>
<style>
:global(.eai3f7b8u) {
  cx: 22.5px;
  cy: 22.2px;
  r: 16.7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.p77bwrbkc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.4 27.4l10.2-10.1l-5-5v19.9l5-5L17.4 17");
}

:global(.qhgja6bzw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.2 34.3l8 8.2");
}

</style>
