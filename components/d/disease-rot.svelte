<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vdv38mb_k"/><path class="u2iqf9blq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:disease-rot" {...props}></Icon>
<style>
:global(.u2iqf9blq) {
  d: path("M9 10a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm2.5 4.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vdv38mb_k) {
  d: path("M6 5c9-1 15 6 13.5 16C10 20 4.5 14 6 5ZM3.5 2.75L6 5");
}

</style>
