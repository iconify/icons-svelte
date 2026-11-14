<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c7sz0bm1r"/><path class="x4j8rst2q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:perspective-correction" {...props}></Icon>
<style>
:global(.c7sz0bm1r) {
  d: path("M3 20.5h18l-3.5-17h-11Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x4j8rst2q) {
  d: path("M9 7h6v10.5H9Z");
}

</style>
