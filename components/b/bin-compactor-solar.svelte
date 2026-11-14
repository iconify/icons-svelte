<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ricg8v11w"/><path class="juiipzc9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bin-compactor-solar" {...props}></Icon>
<style>
:global(.juiipzc9x) {
  d: path("M4.25 19.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm12.5-1.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0ZM18 15v-1m0 7v1m-3-4h-1m7 0h1m-6.25-2.25L15 15m5.25.75L21 15m-5.25 5.25L15 21m5.25-.75L21 21");
}

:global(.ricg8v11w) {
  d: path("M2.75 3.25h11m-2.526 14.5H5L4 6h8.5l-.516 8.084");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
