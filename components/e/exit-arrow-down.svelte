<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpch8ibxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:exit-arrow-down" {...props}></Icon>
<style>
:global(.xpch8ibxs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 16V4.5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2V16m-7-9v14.5M8.5 18l3.5 3.5l3.5-3.5");
}

</style>
