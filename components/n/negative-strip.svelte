<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="jr97ekbvz"/><path class="vgi7r_3nt"/><rect class="vphmwqbdj"/><rect class="b72yrwb4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:negative-strip" {...props}></Icon>
<style>
:global(.b72yrwb4z) {
  width: 5.5px;
  height: 4px;
  x: 13.25px;
  y: 10px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 0.75px;
}

:global(.jr97ekbvz) {
  width: 18.5px;
  height: 14.5px;
  x: 2.75px;
  y: 4.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.75px;
}

:global(.vgi7r_3nt) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 7.25h.01m3.99 0h.01m3.99 0h.01m3.99 0h.01M6 16.75h.01m3.99 0h.01m3.99 0h.01m3.99 0h.01");
}

:global(.vphmwqbdj) {
  width: 5.5px;
  height: 4px;
  x: 5.25px;
  y: 10px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 0.75px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
