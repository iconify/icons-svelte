<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wc1yxsb3w"/><path class="l4rz0smqz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:coffee-machine-sharp" {...props}></Icon>
<style>
:global(.l4rz0smqz) {
  d: path("M15.25 11H17a2.5 2.5 0 0 1 0 5h-1.9M7.75 2.75L6.67 3.83L7.75 5l1.038 1.125L7.75 7.25m3.5-4.5l-1.08 1.08L11.25 5l1.038 1.125L11.25 7.25");
}

:global(.wc1yxsb3w) {
  d: path("M3.75 9.75h11.5v5.75A5.25 5.25 0 0 1 10 20.75H9a5.25 5.25 0 0 1-5.25-5.25Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
