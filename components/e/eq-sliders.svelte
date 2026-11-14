<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvendlbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:eq-sliders" {...props}></Icon>
<style>
:global(.rvendlbcz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3v18m6-18v18m6-18v18M4 13h4v3.5H4Zm6-7h4v3.5h-4Zm6 4h4v3.5h-4Z");
}

</style>
