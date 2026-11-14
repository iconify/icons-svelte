<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="diuhcab9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fixative-spray" {...props}></Icon>
<style>
:global(.diuhcab9f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9.5H13v12H3.5Zm2.5-5h4.5v5H6ZM14 6h.01m3.49-2h.01M18 8.25h.01M21 6h.01");
}

</style>
