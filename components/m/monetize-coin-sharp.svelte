<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="jg7xt1_6k"/><path class="i1xoa_blq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:monetize-coin-sharp" {...props}></Icon>
<style>
:global(.i1xoa_blq) {
  d: path("m12 11.75l-.538-1H8v1.5c0 2 4 1 4 3v1.5H8.538l-.538-1m2-6v1m0 6.5v1m5.75-15.5h5.5v5.5m0-5.5l-5 5");
}

:global(.jg7xt1_6k) {
  cx: 10px;
  cy: 14px;
  r: 7.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
