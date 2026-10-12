<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bvma_qtjv"/><circle class="bij3zcbco"/><circle class="xfgecdbpk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:range-slider-sharp" {...props}></Icon>
<style>
:global(.bij3zcbco) {
  cx: 7.5px;
  cy: 12px;
  r: 2.5px;
}

:global(.bvma_qtjv) {
  d: path("M3.75 12H5m14 0h1.25M10 12h4");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xfgecdbpk) {
  cx: 16.5px;
  cy: 12px;
  r: 2.5px;
}

</style>
