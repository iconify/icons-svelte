<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="yqixzln3k"/><circle class="zt5ju8ikv"/><path class="rg_wy7bnr"/><path class="xyw98ub3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:passwords" {...props}></Icon>
<style>
:global(.rg_wy7bnr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.01 27H43.5v-6H17.009");
}

:global(.xyw98ub3z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.5 21v11H36v-1a2 2 0 1 1 4 0v1h3.5v-5");
}

:global(.yqixzln3k) {
  cx: 14px;
  cy: 24px;
  r: 9.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.zt5ju8ikv) {
  cx: 14px;
  cy: 24px;
  r: 4.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
