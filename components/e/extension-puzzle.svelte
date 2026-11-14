<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dchu32b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:extension-puzzle" {...props}></Icon>
<style>
:global(.dchu32b0h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7.5h5.25a2.5 2.5 0 0 1 5 0H18v4.25a2.5 2.5 0 0 1 0 5V21h-4.25a2.5 2.5 0 0 0-5 0H3.5Z");
}

</style>
