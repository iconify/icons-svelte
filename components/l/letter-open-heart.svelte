<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="la5qfrrxr"/><path class="g7fdkkdhv"/><path class="j-kr2_bru"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:letter-open-heart" {...props}></Icon>
<style>
:global(.g7fdkkdhv) {
  d: path("m3.5 6.5l7.3 5.7a2 2 0 0 0 2.4 0l7.3-5.7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j-kr2_bru) {
  d: path("M12 16.85c-1.58-1.16-2.63-2.1-2.63-3.26c0-.79.58-1.37 1.31-1.37c.58 0 1.05.32 1.31.79c.26-.47.73-.79 1.31-.79c.73 0 1.31.58 1.31 1.37c0 1.16-1.05 2.1-2.63 3.26Z");
}

:global(.la5qfrrxr) {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 5.25px;
  rx: 2.5px;
}

</style>
