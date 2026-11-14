<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etsufwbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bait-bucket" {...props}></Icon>
<style>
:global(.etsufwbre) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 8h14l-1.5 13h-11Zm0 0c0-5.5 14-5.5 14 0M5.5 11.5h13m-8.5 4h.01m3.99 0h.01");
}

</style>
