<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5th9-kvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:offshore-crane" {...props}></Icon>
<style>
:global(.o5th9-kvr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 18h19M5 18v3.5M19 18v3.5M8 8.5h1.5A1.5 1.5 0 0 1 11 10v6.5A1.5 1.5 0 0 1 9.5 18H8a1.5 1.5 0 0 1-1.5-1.5V10A1.5 1.5 0 0 1 8 8.5m3 0L20.5 3m0 0v7.5");
}

</style>
