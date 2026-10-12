<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="km3umabsm"/><path class="xbynfubzo"/><rect class="hj_7tg0dx"/><path class="dgrycpbub"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:referendum" {...props}></Icon>
<style>
:global(.dgrycpbub) {
  d: path("m15.5 9l3.5 3.5M19 9l-3.5 3.5M2.75 19.25h18.5");
}

:global(.hj_7tg0dx) {
  width: 8px;
  height: 8px;
  x: 13.25px;
  y: 6.75px;
  rx: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.km3umabsm) {
  width: 8px;
  height: 8px;
  x: 2.75px;
  y: 6.75px;
  rx: 2px;
}

:global(.xbynfubzo) {
  d: path("M4.75 10.75L6.5 12.5l2.75-3");
}

</style>
