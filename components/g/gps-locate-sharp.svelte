<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="shvec_xgt"/><circle class="ons53cb4g"/><path class="b9fbe6bhi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:gps-locate-sharp" {...props}></Icon>
<style>
:global(.b9fbe6bhi) {
  d: path("M12 2.75V5.5m0 13v2.75M2.75 12H5.5m13 0h2.75");
}

:global(.ons53cb4g) {
  cx: 12px;
  cy: 12px;
  r: 2.5px;
}

:global(.shvec_xgt) {
  cx: 12px;
  cy: 12px;
  r: 6.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
