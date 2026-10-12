<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lnem47ogf"/><circle class="zufhtjckp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lens-hood-sharp" {...props}></Icon>
<style>
:global(.lnem47ogf) {
  d: path("M6.31 4.71a9.25 9.25 0 0 1 11.38 0q-1.17 3.5.49 4a7 7 0 0 1 0 6.58q-1.66.5-.49 4a9.25 9.25 0 0 1-11.38 0q1.17-3.5-.49-4a7 7 0 0 1 0-6.58q1.66-.5.49-4Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zufhtjckp) {
  cx: 12px;
  cy: 12px;
  r: 3.75px;
}

</style>
