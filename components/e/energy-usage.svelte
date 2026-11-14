<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vkxha8b-w"/><path class="jg-fi8rtf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:energy-usage" {...props}></Icon>
<style>
:global(.jg-fi8rtf) {
  d: path("M7 6.5h10v5H7ZM19.25 15l-3.5 3.5h4.5l-3.5 3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vkxha8b-w) {
  d: path("M10.3 20H3.5V3h17v9.3");
}

</style>
