<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gv-wb0bxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:indicator-paper" {...props}></Icon>
<style>
:global(.gv-wb0bxt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 21.5V4l1.5-1.5L12 4l1.5-1.5L15 4v17.5ZM9 12h6m-6 3h6m-6 3h6");
}

</style>
