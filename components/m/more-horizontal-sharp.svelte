<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="zf18uhbyq"/><circle class="lf940mbnz"/><circle class="n0_s6y1ca"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:more-horizontal-sharp" {...props}></Icon>
<style>
:global(.lf940mbnz) {
  cx: 12px;
  cy: 12px;
  r: 1.25px;
}

:global(.n0_s6y1ca) {
  cx: 19.25px;
  cy: 12px;
  r: 1.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zf18uhbyq) {
  cx: 4.75px;
  cy: 12px;
  r: 1.25px;
}

</style>
