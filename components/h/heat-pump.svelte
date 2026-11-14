<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="swegyjmzr"/><path class="j1qtl3p2o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:heat-pump" {...props}></Icon>
<style>
:global(.j1qtl3p2o) {
  d: path("M5 11.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm0 0h9M9.5 7v9m7.25-7.5H19m-2.25 3H19m-2.25 3H19");
}

:global(.swegyjmzr) {
  d: path("M2.5 4.5h19v14h-19Zm3 14V21m13-2.5V21");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
