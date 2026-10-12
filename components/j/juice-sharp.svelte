<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="m-79nlbcc"/><path class="jqtnobcpa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:juice-sharp" {...props}></Icon>
<style>
:global(.jqtnobcpa) {
  d: path("m12.75 12.25l2-9.5h3M6.4 12.25h11.2");
}

:global(.m-79nlbcc) {
  d: path("M5.75 7.75h12.5l-1.4 12.1l-.094 1.403l-1.406-.003h-6.7l-1.406.003l-.094-1.403Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
