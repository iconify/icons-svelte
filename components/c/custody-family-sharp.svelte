<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dcdwgqbou"/><circle class="lr1jhjbei"/><path class="aphn9mb4q"/><circle class="bj2otrpqp"/><path class="cyjzweb3h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:custody-family-sharp" {...props}></Icon>
<style>
:global(.aphn9mb4q) {
  d: path("M4.5 18.75a3.5 3.5 0 0 1 7 0v2.5h-7v-1Z");
}

:global(.bj2otrpqp) {
  cx: 16px;
  cy: 14px;
  r: 1.6px;
}

:global(.cyjzweb3h) {
  d: path("M13.75 19.5a2.25 2.25 0 0 1 4.5 0v1.75h-4.5v-1Z");
}

:global(.dcdwgqbou) {
  d: path("M3.25 9.75L12 3.25l8.75 6.5");
}

:global(.lr1jhjbei) {
  cx: 8px;
  cy: 11.5px;
  r: 2px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
