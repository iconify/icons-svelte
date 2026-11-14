<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="on7q1lb8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:butterfly-table" {...props}></Icon>
<style>
:global(.on7q1lb8s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 5h11v2.5h-11Zm0 1.25L4 12.5m13.5-6.25L20 12.5m-8-5v9M7.5 19l4.5-2.5l4.5 2.5");
}

</style>
