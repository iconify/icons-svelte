<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ng74n8q0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:park-nearby" {...props}></Icon>
<style>
:global(.ng74n8q0j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12.5h19V15h-19Zm2.5-7h14M5 9h14M6.5 5.5v7m11-7v7M5 15l-1 6.5M19 15l1 6.5");
}

</style>
