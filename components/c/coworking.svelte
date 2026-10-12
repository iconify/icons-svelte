<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="qu3-hqbsn"/><circle class="s2aba_b7h"/><rect class="pf5_pbj3q"/><rect class="weciplc9o"/><path class="vj6gb6bph"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:coworking" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pf5_pbj3q) {
  width: 6px;
  height: 5.5px;
  x: 4.25px;
  y: 9.5px;
  rx: 1px;
}

:global(.qu3-hqbsn) {
  cx: 7.25px;
  cy: 4.75px;
  r: 1.75px;
}

:global(.s2aba_b7h) {
  cx: 16.75px;
  cy: 4.75px;
  r: 1.75px;
}

:global(.vj6gb6bph) {
  d: path("M2.75 15h18.5m-16 0v6.25M18.75 15v6.25");
}

:global(.weciplc9o) {
  width: 6px;
  height: 5.5px;
  x: 13.75px;
  y: 9.5px;
  rx: 1px;
}

</style>
