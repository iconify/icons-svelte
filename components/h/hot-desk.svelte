<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bd_1qj7az"/><rect class="vh84y-bdn"/><path class="ctwjpc5en"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hot-desk" {...props}></Icon>
<style>
:global(.bd_1qj7az) {
  d: path("M7.25 4.75h9.5M15 3l1.75 1.75L15 6.5m1.75 3.75h-9.5M9 8.5l-1.75 1.75L9 12");
}

:global(.ctwjpc5en) {
  d: path("M5.5 18v3.25m13-3.25v3.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vh84y-bdn) {
  width: 18.5px;
  height: 3px;
  x: 2.75px;
  y: 15px;
  rx: 1.5px;
}

</style>
