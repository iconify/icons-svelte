<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf5bfgbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:drone-altitude" {...props}></Icon>
<style>
:global(.yf5bfgbze) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5h6m7 0h6m-16 0v4.5h13V5m-3.9 9.5H8v-5h8v2.7m2 8.8v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
