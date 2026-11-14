<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxbcoqbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:momentum" {...props}></Icon>
<style>
:global(.sxbcoqbts) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 12a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Zm-7.5 0H7M4.5 8H8m-3.5 8H8");
}

</style>
