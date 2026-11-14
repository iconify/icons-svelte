<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3dhywbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:plane-detection" {...props}></Icon>
<style>
:global(.t3dhywbvl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 16.5H21L17.5 21H3Zm-2-10V3H8m8 0h3.5v3.5M4.5 10v3.5H8M19.5 10v3.5H16");
}

</style>
