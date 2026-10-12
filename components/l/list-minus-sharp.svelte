<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="lcmqtccog"/><path class="wqbhr255g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:list-minus-sharp" {...props}></Icon>
<style>
:global(.lcmqtccog) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 6h11m-11 6h11m-11 6h11");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.wqbhr255g) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.25 6h.01m-.01 6h.01m-.01 6h.01");
}

</style>
