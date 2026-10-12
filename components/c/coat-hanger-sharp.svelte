<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uz6rs8bdx"/><path class="nux34_pfc"/><path class="zari_e5dk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:coat-hanger-sharp" {...props}></Icon>
<style>
:global(.nux34_pfc) {
  d: path("m12.65 9.12l7.95 4.51l.65.37v3.5l-.65-.37l-7.95-4.51l-.65-.37l-.65.37l-7.95 4.51l-.65.37V14l.65-.37l7.95-4.51l.65-.37z");
}

:global(.uz6rs8bdx) {
  d: path("M9.75 5A2.25 2.25 0 1 1 12 7.25v2");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zari_e5dk) {
  d: path("M5.25 16.5v3.75h13.5V16.5");
}

</style>
