<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5j413c_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:business-model" {...props}></Icon>
<style>
:global(.x5j413c_s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5H7v3L5.5 9h-3Zm7.25 0h4.5v3L12.75 9h-3Zm7.25 0h4.5v3L20 9h-3Zm-11 8h4.5v3L9 17H6Zm7.5 0H18v3L16.5 17h-3Zm-11 8h19");
}

</style>
