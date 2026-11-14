<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uyqkx0uyr"/><path class="a-b_3nb4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dewdrop" {...props}></Icon>
<style>
:global(.a-b_3nb4z) {
  d: path("m12 8.75l2.25 3a2.5 2.5 0 1 1-4.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uyqkx0uyr) {
  d: path("M4 20C3 9 9 3 20 4c1 11-5 17-16 16Zm-1.5 1.5L4 20");
}

</style>
