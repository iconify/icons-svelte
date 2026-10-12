<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="psizqf3sa"/><path class="pxf9mqb_m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:planner-book-sharp" {...props}></Icon>
<style>
:global(.psizqf3sa) {
  d: path("M4.75 2.75h14.5v18.5H4.75zm3.5 0v18.5");
}

:global(.pxf9mqb_m) {
  d: path("M11.5 2.75H15v7L13.25 8.5L11.5 9.75Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
