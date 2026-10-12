<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="vhm2msbhv"/><path class="clb5eab5l"/><rect class="lx-87bbdr"/><rect class="q4x9zidoh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:eyeshadow-palette" {...props}></Icon>
<style>
:global(.clb5eab5l) {
  d: path("M2.75 7.75h18.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lx-87bbdr) {
  width: 4.75px;
  height: 6px;
  x: 5.75px;
  y: 10.75px;
  rx: 1.25px;
}

:global(.q4x9zidoh) {
  width: 4.75px;
  height: 6px;
  x: 13.5px;
  y: 10.75px;
  rx: 1.25px;
}

:global(.vhm2msbhv) {
  width: 18.5px;
  height: 15.5px;
  x: 2.75px;
  y: 4.25px;
  rx: 2.5px;
}

</style>
