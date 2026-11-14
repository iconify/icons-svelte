<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="az8c50bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cricket-yorker" {...props}></Icon>
<style>
:global(.az8c50bmh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 21V6.25M8.5 21V6.25m4 14.75V6.25m-9-2.75h10m1.75 14.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

</style>
