<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j6lvvsbhz"/><rect class="f2al7r3cg"/><rect class="eut0kccpp"/><rect class="mrf30ffck"/><path class="a418j7qgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:coronacheck" {...props}></Icon>
<style>
:global(.a418j7qgd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.5 29.5h3v3h-3zm3-3h3v3h-3zm0 6h3v3h-3zm-6-6h3v3h-3zm0 6h3v3h-3z");
}

:global(.eut0kccpp) {
  width: 9px;
  height: 9px;
  x: 12.5px;
  y: 26.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
}

:global(.f2al7r3cg) {
  width: 9px;
  height: 9px;
  x: 12.5px;
  y: 12.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
}

:global(.j6lvvsbhz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 19.5v-14h-37v14a4.5 4.5 0 0 1 0 9v14h37v-14a4.5 4.5 0 0 1 0-9");
}

:global(.mrf30ffck) {
  width: 9px;
  height: 9px;
  x: 26.5px;
  y: 12.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
}

</style>
