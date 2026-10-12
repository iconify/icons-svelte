<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="rf72_lb5i"/><circle class="e1_x4r67w"/><circle class="wft9rcgmo"/><path class="zvewilb8r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:alternator-sharp" {...props}></Icon>
<style>
:global(.e1_x4r67w) {
  cx: 4.75px;
  cy: 4.75px;
  r: 2px;
}

:global(.rf72_lb5i) {
  cx: 12px;
  cy: 13.5px;
  r: 7px;
}

:global(.wft9rcgmo) {
  cx: 19.25px;
  cy: 4.75px;
  r: 2px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zvewilb8r) {
  d: path("m13.09 9.76l-3.28 3.93l-.26.31h1.1v3.55l.23-.33l3.39-4.74l.23-.33h-1.15v-2.7z");
}

</style>
