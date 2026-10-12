<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="d2de6_b_n"/><path class="m7hlo1bxu"/><path class="zh70awb4u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:password" {...props}></Icon>
<style>
:global(.d2de6_b_n) {
  width: 18.5px;
  height: 10.5px;
  x: 2.75px;
  y: 6.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.m7hlo1bxu) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 12h.01m3.49 0h.01M14 12h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.zh70awb4u) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.5 9.75v4.5");
}

</style>
