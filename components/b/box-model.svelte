<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6ulkabjn"/><path class="ekxv2q3-d"/><path class="j_6cnd1gh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:box-model" {...props}></Icon>
<style>
:global(.ekxv2q3-d) {
  d: path("M6 6h12v12H6Z");
}

:global(.g6ulkabjn) {
  d: path("M2.5 2.5h19v19h-19Z");
}

:global(.j_6cnd1gh) {
  d: path("M9.5 9.5h5v5h-5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
