<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sir87dgiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:potted-plant-small" {...props}></Icon>
<style>
:global(.sir87dgiz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 13.5h11l-1.5 8H8Zm5.5 0V9m0 1c-3.5 0-6-2-6-5.5c3.5 0 6 2 6 5.5Zm0-1c3.5 0 6-2 6-5.5c-3.5 0-6 2-6 5.5Z");
}

</style>
