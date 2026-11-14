<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2a2tvb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:artboard-resize" {...props}></Icon>
<style>
:global(.j2a2tvb4s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 5h10.5M19 6.75v10.5M17.25 19H6.75M5 17.25V6.75m-1.75-3.5h3.5v3.5h-3.5Zm14 0h3.5v3.5h-3.5Zm-14 14h3.5v3.5h-3.5Zm14 0h3.5v3.5h-3.5ZM9 15l6-6m-4 0h4v4");
}

</style>
