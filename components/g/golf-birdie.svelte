<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yv14z3bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:golf-birdie" {...props}></Icon>
<style>
:global(.yv14z3bac) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 8.5q3.25-5.5 6.75 0q3.5-5.5 6.75 0M3 17.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm7.5-3.75q2-1.75 5-2.25");
}

</style>
