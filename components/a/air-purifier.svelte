<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="kjyo-to4o"/><circle class="pei_pcr2y"/><path class="vyyejfj4b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:air-purifier" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kjyo-to4o) {
  width: 12.5px;
  height: 11.75px;
  x: 5.75px;
  y: 9.5px;
  rx: 3px;
}

:global(.pei_pcr2y) {
  cx: 12px;
  cy: 15.375px;
  r: 2.75px;
}

:global(.vyyejfj4b) {
  d: path("M7.75 3.5c1.4 1 2.85-1 4.25 0s2.85 1 4.25 0m-8.5 3c1.4 1 2.85-1 4.25 0s2.85 1 4.25 0");
}

</style>
