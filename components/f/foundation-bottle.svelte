<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rvju9hbwv"/><rect class="idefk2byg"/><path class="ouj8_h6ip"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:foundation-bottle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.idefk2byg) {
  width: 13.5px;
  height: 11.5px;
  x: 5.25px;
  y: 9.75px;
  rx: 2.5px;
}

:global(.ouj8_h6ip) {
  d: path("M7.5 15c1.5-.75 3 .75 4.5 0s3-.75 4.5 0");
}

:global(.rvju9hbwv) {
  width: 6px;
  height: 4px;
  x: 9px;
  y: 2.75px;
  rx: 1.25px;
}

</style>
