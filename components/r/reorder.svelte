<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhri1mb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:reorder" {...props}></Icon>
<style>
:global(.nhri1mb8o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 6h10m-10 6h10m-10 6h10M5 4v16M2.5 6.5L5 4l2.5 2.5m-5 11L5 20l2.5-2.5");
}

</style>
