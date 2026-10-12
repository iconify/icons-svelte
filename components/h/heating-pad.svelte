<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="seij8zbco"/><path class="k23r_5t_x"/><rect class="msqg5aclg"/><path class="xywfz8byv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:heating-pad" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k23r_5t_x) {
  d: path("M2.75 13.5H15.5M2.75 17.25H15.5m0-1.75H18");
}

:global(.msqg5aclg) {
  width: 3.25px;
  height: 6.25px;
  x: 18px;
  y: 12.5px;
  rx: 1.25px;
}

:global(.seij8zbco) {
  width: 12.75px;
  height: 11.75px;
  x: 2.75px;
  y: 9.5px;
  rx: 2.25px;
}

:global(.xywfz8byv) {
  d: path("M5.75 2.75Q4.625 3.875 5.75 5c1.125 1.125.75 1.5 0 2.25m3.75-4.5Q8.375 3.875 9.5 5c1.125 1.125.75 1.5 0 2.25m3.75-4.5q-1.125 1.125 0 2.25c1.125 1.125.75 1.5 0 2.25");
}

</style>
