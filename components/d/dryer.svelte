<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="g6ctus9qt"/><path class="ms_j_3bnt"/><circle class="lvri69kam"/><path class="fhirbxv7r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dryer" {...props}></Icon>
<style>
:global(.fhirbxv7r) {
  d: path("M10.4 11.75c-.75.67-.75 1.33 0 2s.75 1.33 0 2m3.2-4c-.75.67-.75 1.33 0 2s.75 1.33 0 2");
}

:global(.g6ctus9qt) {
  width: 16.5px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  rx: 2.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lvri69kam) {
  cx: 12px;
  cy: 13.75px;
  r: 5px;
}

:global(.ms_j_3bnt) {
  d: path("M10 5.5h4");
}

</style>
