<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="trxlteb6d"/><path class="seoptyj0w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:esg-letters-badge" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.seoptyj0w) {
  d: path("M8.75 15.75L7.5 21.5l2.25-1.25L12 21.5l2.25-1.25l2.25 1.25l-1.25-5.75M9 12c0-3 2-5 6-5c0 3-2 5-6 5");
}

:global(.trxlteb6d) {
  d: path("M5 9.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0");
}

</style>
