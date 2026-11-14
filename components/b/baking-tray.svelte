<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1n7tc9ac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:baking-tray" {...props}></Icon>
<style>
:global(.j1n7tc9ac) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11.5h19l-2 4.5h-15Zm0 0C2.5 7 7 7 7 11.5m2.75 0c0-4.5 4.5-4.5 4.5 0m2.75 0c0-4.5 4.5-4.5 4.5 0");
}

</style>
