<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nnfrnsbna"/><path class="hh8d8ru8d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:monastery-sharp" {...props}></Icon>
<style>
:global(.hh8d8ru8d) {
  d: path("M10.5 6.75V3h3v3.75M10 21.25V15.5h4v5.75");
}

:global(.nnfrnsbna) {
  d: path("m12.42 6.01l8.41 5.23l.42.26H19.5v9.75h-15V11.5H2.75l.42-.26l8.41-5.23l.42-.26z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
