<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gp904e3zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cam-mechanism" {...props}></Icon>
<style>
:global(.gp904e3zg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.5 15c0 2.5-5 5.5-9.5 5.5c-3.5 0-5.5-2.5-5.5-5.5s2-5.5 5.5-5.5c4.5 0 9.5 3 9.5 5.5M10 2.5v7m-2.25 0h4.5M10 15h.01");
}

</style>
