<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s83m05bmc"/><path class="u_jhvhb9s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:calligraphy-pen" {...props}></Icon>
<style>
:global(.s83m05bmc) {
  d: path("M8.5 2.5h7v4h-7Zm3.5 15l-5.5-6l2.5-5h6l2.5 5Z");
}

:global(.u_jhvhb9s) {
  d: path("M10.5 11a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm1.5 1.5v5M4 21c4-2 12 2 16 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
