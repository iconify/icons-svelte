<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tdt260b1g"/><path class="j_issmbrn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:oven-built-in" {...props}></Icon>
<style>
:global(.j_issmbrn) {
  d: path("M7.5 12h9v5.5h-9ZM8 6.5h.01m3.99 0h.01");
}

:global(.tdt260b1g) {
  d: path("M4 4h16v16H4Zm0 5h16");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
