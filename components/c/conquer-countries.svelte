<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="a-h_0femp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:conquer-countries" {...props}></Icon>
<style>
:global(.a-h_0femp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.125 20l-2.65 8l-2.65-8m7.209 7.124c.49.638 1.105.876 1.961.876h1.184a1.996 1.996 0 0 0 1.996-1.996v-.008A1.996 1.996 0 0 0 28.18 24h-1.306a2 2 0 0 1-1.998-1.998h0c0-1.106.897-2.002 2.002-2.002h1.178c.856 0 1.471.238 1.962.877M6.672 41.328l10.672-10.672m13.312-13.312L41.301 6.699");
}

:global(.j3s9ivbxi) {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
