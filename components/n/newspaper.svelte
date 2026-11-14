<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yg5c6ykby"/><path class="up4_lo--o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:newspaper" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.up4_lo--o) {
  d: path("M8 7.5h4A1.5 1.5 0 0 1 13.5 9v1a1.5 1.5 0 0 1-1.5 1.5H8A1.5 1.5 0 0 1 6.5 10V9A1.5 1.5 0 0 1 8 7.5m-1.5 7h7m-7 2.5H11");
}

:global(.yg5c6ykby) {
  d: path("M17 20H5.5A2.5 2.5 0 0 1 3 17.5v-12A1.5 1.5 0 0 1 4.5 4h11A1.5 1.5 0 0 1 17 5.5V18a2 2 0 0 0 4 0V9h-4Z");
}

</style>
