<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><circle class="uadx0728c"/><circle class="xnt5zf0il"/><path class="o4z5kmbus"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:interest-rate-sharp" {...props}></Icon>
<style>
:global(.dbgvcxwad) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

:global(.o4z5kmbus) {
  d: path("m15.5 8.5l-7 7");
}

:global(.uadx0728c) {
  cx: 9.25px;
  cy: 9.25px;
  r: 1.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xnt5zf0il) {
  cx: 14.75px;
  cy: 14.75px;
  r: 1.5px;
}

</style>
