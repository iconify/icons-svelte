<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a4w_o_bst"/><path class="o_j1wbbzw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:junction-box" {...props}></Icon>
<style>
:global(.a4w_o_bst) {
  d: path("M6 4h12v16H6Zm-4 8h4m12 0h4");
}

:global(.o_j1wbbzw) {
  d: path("M9 9.5h6v5H9Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
