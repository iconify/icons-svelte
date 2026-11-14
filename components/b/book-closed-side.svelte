<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lw_fv4jah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:book-closed-side" {...props}></Icon>
<style>
:global(.lw_fv4jah) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21 6H6.5A3.5 3.5 0 0 0 3 9.5v5A3.5 3.5 0 0 0 6.5 18H21M8 10h13M8 14h13");
}

</style>
