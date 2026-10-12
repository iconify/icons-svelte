<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="nw4bqebzp"/><path class="mjlgppbma"/><path class="c4hhgzm0t"/><path class="x1xndnbvq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lottery-ticket" {...props}></Icon>
<style>
:global(.c4hhgzm0t) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.5 9.5h.01m3.24 0h.01m3.24 0h.01");
}

:global(.mjlgppbma) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 7.5V9m0 2.25v1.5M8 15v1.5");
}

:global(.nw4bqebzp) {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 5.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

:global(.x1xndnbvq) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 14.5H18");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
