<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n-9tk3bho"/><path class="ez9d3ktpn"/><path class="itxyfybyu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:nursery-glider" {...props}></Icon>
<style>
:global(.ez9d3ktpn) {
  d: path("M6.75 9.5h9.75v9.75M8 13.5v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.itxyfybyu) {
  d: path("M3 17.5q9 5 18 0");
}

:global(.n-9tk3bho) {
  d: path("m5.5 3l2 10.5h10");
}

</style>
