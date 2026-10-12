<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="o9qffsbrd"/><path class="uz8ke0aqn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bolt-cutter-sharp" {...props}></Icon>
<style>
:global(.o9qffsbrd) {
  d: path("m12.58 3.22l1.59 1.31l.58.47l-.18.73l-.39 1.54L14 8h-4l-.18-.73l-.39-1.54L9.25 5l.58-.47l1.59-1.31l.58-.47z");
}

:global(.uz8ke0aqn) {
  d: path("M9.5 7.75h5v3.5h-5zm2.5-2.5V8m-1.25 3.25L7.5 17m5.75-5.75L16.5 17m-9.08-.66l.66.32l.67.34l-.38.65l-1.74 2.95l-.38.65l-.67-.34l-.66-.32l-.67-.34l.38-.65l1.74-2.95l.38-.65zm10.21.31l1.74 2.95l.38.65l-.67.34l-.66.32l-.67.34l-.38-.65l-1.74-2.95l-.38-.65l.67-.34l.66-.32l.67-.34z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
