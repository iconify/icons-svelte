<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c7dgfu7wx"/><path class="oy6o-dbxk"/><path class="o1_lmbxyf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:curtain-outline-regular" {...props}></Icon>
<style>
:global(.c7dgfu7wx) {
  d: path("M2 4h20");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o1_lmbxyf) {
  d: path("M21 4v17h-5c-1.5 0 -2 -1 -2 -3V4");
}

:global(.oy6o-dbxk) {
  d: path("M3 4v17h5c1.5 0 2 -1 2 -3V4");
}

</style>
