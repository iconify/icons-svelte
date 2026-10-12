<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jwtqgtovq"/><circle class="t5l-0hb6o"/><circle class="ww-9niimv"/><circle class="keddctbnm"/><circle class="cwdidobis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:abacus-sharp" {...props}></Icon>
<style>
:global(.cwdidobis) {
  cx: 16.5px;
  cy: 15px;
  r: 1.5px;
}

:global(.jwtqgtovq) {
  d: path("M5.25 3.75h16v16.5H2.75V3.75zM2.75 9H6m3 0h3m3 0h6.25m-18.5 6H9m3 0h3m3 0h3.25");
}

:global(.keddctbnm) {
  cx: 10.5px;
  cy: 15px;
  r: 1.5px;
}

:global(.t5l-0hb6o) {
  cx: 7.5px;
  cy: 9px;
  r: 1.5px;
}

:global(.ww-9niimv) {
  cx: 13.5px;
  cy: 9px;
  r: 1.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
