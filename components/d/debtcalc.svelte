<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="uhx3m_1tm"/><path class="gr6i86b-i"/><path class="nhbyowbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:debtcalc" {...props}></Icon>
<style>
:global(.gr6i86b-i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.533 7.963h24.935v6.575H11.533zm0 10.037h6v5.278h-6zm0 8.329h6v5.278h-6zm-.001 8.328h6v5.278h-6zM21 18h6v5.278h-6zm0 8.328h6v5.278h-6zm0 8.329h6v5.278h-6zM30.467 18h6v5.278h-6zm.001 8.328h6v5.278h-6zm-.001 8.328h6v5.278h-6zm.374-23.411h-2.028");
}

:global(.nhbyowbhl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.996 10.407l1.13-.662v3");
}

:global(.uhx3m_1tm) {
  width: 31px;
  height: 39px;
  x: 8.5px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
