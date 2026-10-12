<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="zf3dw5w8a"/><path class="st05ixb5o"/><circle class="aoknrac1h"/><circle class="ryeuqv1om"/><path class="pnfkp7bqz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:intermodal" {...props}></Icon>
<style>
:global(.aoknrac1h) {
  cx: 5.75px;
  cy: 18.5px;
  r: 1.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pnfkp7bqz) {
  d: path("M14 19.25c1.2-1 2.3-1 3.5 0s2.55 1 3.75 0");
}

:global(.ryeuqv1om) {
  cx: 10.25px;
  cy: 18.5px;
  r: 1.75px;
}

:global(.st05ixb5o) {
  d: path("M10.17 4.25v7m3.66-7v7M2.75 14.5h18.5");
}

:global(.zf3dw5w8a) {
  width: 11px;
  height: 7px;
  x: 6.5px;
  y: 4.25px;
  rx: 1px;
}

</style>
