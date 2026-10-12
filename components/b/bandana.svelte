<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cuc-wmbmz"/><rect class="tgwndpv4a"/><path class="zoz0n1_5p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bandana" {...props}></Icon>
<style>
:global(.cuc-wmbmz) {
  d: path("M4.25 10h15.5q1.5 0 .55 1.16l-7.35 8.93q-.95 1.16-1.9 0L3.7 11.16Q2.75 10 4.25 10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tgwndpv4a) {
  width: 3.5px;
  height: 3.25px;
  x: 10.25px;
  y: 4.25px;
  rx: 1.25px;
}

:global(.zoz0n1_5p) {
  d: path("M10.25 5.25L7 3.25m6.75 2l3.25-2m-3.75 15c-2.75-1.25-3-5.25-.25-5.5c1.5-.1 2.25 1.75.75 2.5");
}

</style>
