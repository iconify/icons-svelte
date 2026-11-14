<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmznx-b8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:boss-health" {...props}></Icon>
<style>
:global(.nmznx-b8e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 10V5.5l2 2L7 4.75L8.5 7.5l2-2V10Zm-1 3h19v6.5h-19Zm3 3.25h10.25");
}

</style>
