<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rm929_bat"/><circle class="g_r9k1kci"/><circle class="c0yewh3tu"/><path class="p75jvb5ex"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chain-of-thought" {...props}></Icon>
<style>
:global(.c0yewh3tu) {
  cx: 4px;
  cy: 20px;
  r: 1.25px;
}

:global(.g_r9k1kci) {
  cx: 6.75px;
  cy: 15.75px;
  r: 1.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p75jvb5ex) {
  d: path("M15 5q.36 2.64 3 3q-2.64.36-3 3q-.36-2.64-3-3q2.64-.36 3-3");
}

:global(.rm929_bat) {
  width: 12.5px;
  height: 10.5px;
  x: 8.75px;
  y: 2.75px;
  rx: 5.25px;
}

</style>
