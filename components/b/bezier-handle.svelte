<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ko5pe1brz"/><rect class="m653br9ll"/><circle class="g3jvdsbwi"/><circle class="zo34uu--r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bezier-handle" {...props}></Icon>
<style>
:global(.g3jvdsbwi) {
  cx: 4.25px;
  cy: 9px;
  r: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ko5pe1brz) {
  d: path("M10.25 10.75C8 11.25 6 14 5.25 21.25m8.5-10.5c2.25.5 4.25 3.25 5 10.5M5.75 9h4.5m3.5 0h4.5");
}

:global(.m653br9ll) {
  width: 3.5px;
  height: 3.5px;
  x: 10.25px;
  y: 7.25px;
  rx: 0.75px;
}

:global(.zo34uu--r) {
  cx: 19.75px;
  cy: 9px;
  r: 1.5px;
}

</style>
