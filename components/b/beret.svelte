<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjy4_0c1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:beret" {...props}></Icon>
<style>
:global(.jjy4_0c1y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 14.5c-2-4 2.5-8 8-8s10 4 8 8Zm2.5 0h11v2.75h-11Zm5.5-8V4.25");
}

</style>
