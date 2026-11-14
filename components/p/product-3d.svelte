<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kwd6tdbsf"/><path class="u8054pfip"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:product-3d" {...props}></Icon>
<style>
:global(.kwd6tdbsf) {
  d: path("M3.5 7.5L12 3l8.5 4.5v9L12 21l-8.5-4.5Z");
}

:global(.u8054pfip) {
  d: path("M3.5 7.5L12 12l8.5-4.5M12 12v9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
