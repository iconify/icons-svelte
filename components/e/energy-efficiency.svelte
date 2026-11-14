<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="suh_4mbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:energy-efficiency" {...props}></Icon>
<style>
:global(.suh_4mbhs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.092 17.755L17 10h-5.5L13 2.5L5 13h5.5L9 20.5l1.849-2.427M14.75 18l2 2L21 15.75");
}

</style>
