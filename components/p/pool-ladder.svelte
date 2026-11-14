<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z762_lb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pool-ladder" {...props}></Icon>
<style>
:global(.z762_lb5q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 21V7a3 3 0 0 1 6 0v2m3 12V7a3 3 0 0 1 6 0v2m-15 3h9m-9 4.5h9");
}

</style>
