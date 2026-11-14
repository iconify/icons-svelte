<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nm3_1ljtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:gas-leak-survey" {...props}></Icon>
<style>
:global(.nm3_1ljtr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13h8m-8 6h8m3-6h8m-8 6h8m-11-8h3v10h-3ZM12 8q-1.75-1.5 0-3t0-2.5");
}

</style>
