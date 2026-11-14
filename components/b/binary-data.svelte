<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zkc5r1bvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:binary-data" {...props}></Icon>
<style>
:global(.zkc5r1bvj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 4v16M4.5 6.5L7 4m3.5 8a4.5 8 0 1 0 9 0a4.5 8 0 1 0-9 0Z");
}

</style>
