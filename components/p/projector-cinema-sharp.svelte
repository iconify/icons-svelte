<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="qe3spob8a"/><circle class="xascr4b4t"/><path class="enks7630l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:projector-cinema-sharp" {...props}></Icon>
<style>
:global(.enks7630l) {
  d: path("M2.75 12h14v7.75h-14zm14.7.98l3.1-1.21l.7-.27v8l-.7-.27l-3.1-1.21l-.7-.27v-4.5z");
}

:global(.qe3spob8a) {
  cx: 6.25px;
  cy: 6.25px;
  r: 3px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xascr4b4t) {
  cx: 14px;
  cy: 7px;
  r: 2.25px;
}

</style>
