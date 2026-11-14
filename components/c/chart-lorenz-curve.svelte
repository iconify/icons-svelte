<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tmp0jr96l"/><path class="u0j_57b4d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chart-lorenz-curve" {...props}></Icon>
<style>
:global(.tmp0jr96l) {
  d: path("M3.5 3.5v17h17m-17 0l17-17");
}

:global(.u0j_57b4d) {
  d: path("M3.5 20.5q12.5.5 17-17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
