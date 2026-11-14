<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnpcu7bid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:alternate-glyph" {...props}></Icon>
<style>
:global(.fnpcu7bid) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 11.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Zm13-6.5v11.5c0 2.5 1.25 3.5 2.75 3.5s2.25-1 2.25-2.5");
}

</style>
