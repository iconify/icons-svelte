<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kq4x270gg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lightbox-sign" {...props}></Icon>
<style>
:global(.kq4x270gg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 6.5h13v11h-13Zm3 4h7m-7 3H13m-1-11V4m0 16v1.5M2.5 12h1.25m16.5 0h1.25M2.75 2.75L4 4m17.25-1.25L20 4M2.75 21.25L4 20m17.25 1.25L20 20");
}

</style>
