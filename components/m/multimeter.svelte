<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dnp2npbye"/><path class="kcf52vx4u"/><circle class="rh1oi0w6a"/><path class="knq-qlk1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:multimeter" {...props}></Icon>
<style>
:global(.dnp2npbye) {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 2.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kcf52vx4u) {
  d: path("M7.75 5.75h8.5V9.5h-8.5Z");
}

:global(.knq-qlk1t) {
  d: path("m12 15.25l1.5-1.5");
}

:global(.rh1oi0w6a) {
  cx: 12px;
  cy: 15.25px;
  r: 3.25px;
}

</style>
