<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m7w7_mo_p"/><circle class="rsi23vbic"/><path class="nf7ntvb4j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:car-seat-baby" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m7w7_mo_p) {
  d: path("M3.75 4.5h.75q1 0 1 1V14q0 1 1 1h13q1 0 1 1v1q0 1-1 1H3.75q-1 0-1-1V5.5q0-1 1-1");
}

:global(.nf7ntvb4j) {
  d: path("m8.5 15l5-3.5m-10 8.75q8.5 1.5 17 0");
}

:global(.rsi23vbic) {
  cx: 10px;
  cy: 8.5px;
  r: 2px;
}

</style>
