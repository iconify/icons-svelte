<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="j3pmu0w-p"/><path class="txa1wybgb"/><circle class="vjkaz5b6y"/><path class="xpubp99eq"/><circle class="k4qyefyhm"/><path class="lzb9mh8tx"/><circle class="yqfbmc8ul"/><path class="wuoty2bix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:homescapes" {...props}></Icon>
<style>
:global(.j3pmu0w-p) {
  cx: 39.625px;
  cy: 8.92px;
  r: 2.875px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.k4qyefyhm) {
  cx: 8.375px;
  cy: 39.08px;
  r: 2.875px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.lzb9mh8tx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.25 39.08h25.5");
}

:global(.txa1wybgb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.75 8.92h-25.5");
}

:global(.vjkaz5b6y) {
  cx: 8.375px;
  cy: 18.973px;
  r: 2.875px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.wuoty2bix) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.75 29.027h-25.5");
}

:global(.xpubp99eq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.25 18.973h25.5");
}

:global(.yqfbmc8ul) {
  cx: 39.625px;
  cy: 29.027px;
  r: 2.875px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
