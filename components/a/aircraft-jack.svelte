<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7w_a6a0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:aircraft-jack" {...props}></Icon>
<style>
:global(.k7w_a6a0t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 21.5l5.5-6h6l5.5 6M10.25 6h3.5v9.5h-3.5ZM12 3.5V6M7.5 3.5h9");
}

</style>
