<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="raaddvxhx"/><path class="bpnh47tol"/><path class="t8g1vpp5m"/><path class="vf68qibdo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mini-pc" {...props}></Icon>
<style>
:global(.bpnh47tol) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 13h5");
}

:global(.raaddvxhx) {
  width: 18.5px;
  height: 7.5px;
  x: 2.75px;
  y: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

:global(.t8g1vpp5m) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 13h.01");
}

:global(.vf68qibdo) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 19.75h10.5");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
