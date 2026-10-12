<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="f3n1gfb0c"/><path class="ssx2jj5vk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cubicle-sharp" {...props}></Icon>
<style>
:global(.f3n1gfb0c) {
  d: path("M2.75 21.25V4.75h18.5v16.5M2.75 16h18.5");
}

:global(.ssx2jj5vk) {
  d: path("M8.5 8h7v5h-7zm3.5 5v3");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
