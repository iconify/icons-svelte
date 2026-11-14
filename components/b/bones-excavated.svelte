<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjfkjjbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bones-excavated" {...props}></Icon>
<style>
:global(.hjfkjjbrg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 8h10a2 2 0 1 1 2.5 2a2 2 0 1 1-2.5 2H7a2 2 0 1 1-2.5-2A2 2 0 1 1 7 8Zm-4.5 8.5h19M5 20h4m3.5 0h6");
}

</style>
