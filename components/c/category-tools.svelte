<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvgf8wtwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:category-tools" {...props}></Icon>
<style>
:global(.jvgf8wtwg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.5 4.5A4.5 4.5 0 0 0 10 10l-6.5 6.5a2 2 0 0 0 4 4L14 14a4.5 4.5 0 0 0 5.5-4.5l-3 3l-4-4Z");
}

</style>
