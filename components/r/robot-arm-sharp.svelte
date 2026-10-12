<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="yuhh-lb2x"/><circle class="d2lzq481w"/><path class="c875p0zop"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:robot-arm-sharp" {...props}></Icon>
<style>
:global(.c875p0zop) {
  d: path("M19.75 3.25h-3V8.5h3");
}

:global(.d2lzq481w) {
  cx: 6.75px;
  cy: 8.5px;
  r: 2.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yuhh-lb2x) {
  d: path("M4.75 21.25h9.5v-3.5H3.75v3.5zM9 17.75l-1.75-6.5M9.5 7.5l5.75-2");
}

</style>
