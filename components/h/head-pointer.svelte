<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="oyoycy5kq"/><path class="hn97-qi5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:head-pointer" {...props}></Icon>
<style>
:global(.hn97-qi5q) {
  d: path("M2.75 21.25C2.75 18.5 5.25 17 8.5 17s5.75 1.5 5.75 4.25M12.75 6.5L20.5 3M3.25 8.25h10.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oyoycy5kq) {
  cx: 8.5px;
  cy: 9.25px;
  r: 5.25px;
}

</style>
