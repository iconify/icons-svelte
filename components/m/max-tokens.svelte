<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="km7bmwd7z"/><rect class="pj4t9bx_j"/><path class="mkd1vjboj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:max-tokens" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.km7bmwd7z) {
  d: path("M3.75 4.25h16.5m-16.5-1.5v3m16.5-3v3");
}

:global(.mkd1vjboj) {
  d: path("M6.25 13h11.5m-11.5 4h11.5");
}

:global(.pj4t9bx_j) {
  width: 11.5px;
  height: 12.5px;
  x: 6.25px;
  y: 8.75px;
  rx: 2.5px;
}

</style>
