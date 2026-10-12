<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="abez8e7ch"/><path class="xtt85suoa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:blueprint-sharp" {...props}></Icon>
<style>
:global(.abez8e7ch) {
  d: path("M2.75 3.75h18.5v16.5H2.75zm4.25 0v16.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xtt85suoa) {
  d: path("M10.25 7.25h7.5v9.5h-7.5Zm0 4.75h4v4.75");
}

</style>
