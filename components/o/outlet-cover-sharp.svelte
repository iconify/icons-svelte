<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kmwtcf48k"/><path class="umueumbuc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:outlet-cover-sharp" {...props}></Icon>
<style>
:global(.kmwtcf48k) {
  d: path("M5 2.75h14v18.5H5zm5.25 3.5v2m3.5-2v2m-1.75 2v.01");
}

:global(.umueumbuc) {
  d: path("M8 13h8v5.5H8zm2.5 2.75h3");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
