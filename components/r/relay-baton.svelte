<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="i9t0w8bjh"/><path class="uux0pkbhb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:relay-baton" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i9t0w8bjh) {
  width: 13.25px;
  height: 6.5px;
  x: 8px;
  y: 8.75px;
  rx: 3.25px;
}

:global(.uux0pkbhb) {
  d: path("M12.25 8.75v6.5M17 8.75v6.5m-14.25-5H5m-2.25 3.5H5");
}

</style>
