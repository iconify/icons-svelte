<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="em6rsdowp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:column-grid-plan" {...props}></Icon>
<style>
:global(.em6rsdowp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 4.5h15M4.5 12h15m-15 7.5h15m-15-15v15m7.5-15v15m7.5-15v15M3.25 3.25h2.5v2.5h-2.5Zm7.5 0h2.5v2.5h-2.5Zm7.5 0h2.5v2.5h-2.5Zm-15 7.5h2.5v2.5h-2.5Zm7.5 0h2.5v2.5h-2.5Zm7.5 0h2.5v2.5h-2.5Zm-15 7.5h2.5v2.5h-2.5Zm7.5 0h2.5v2.5h-2.5Zm7.5 0h2.5v2.5h-2.5Z");
}

</style>
