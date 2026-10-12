<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vt1k1yv9q"/><path class="m6bm-rb3x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dialysis-machine-sharp" {...props}></Icon>
<style>
:global(.m6bm-rb3x) {
  d: path("M7 5h6.5v4.5H7zm.5 8.25H9m2.5 0H13M7.5 17h6m2.25-8.75h4v10.5h-3.5");
}

:global(.vt1k1yv9q) {
  d: path("M4.75 2.75h11v18.5h-11z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
