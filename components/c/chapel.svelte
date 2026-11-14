<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pp7umkmgo"/><path class="fsnfx25hs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chapel" {...props}></Icon>
<style>
:global(.fsnfx25hs) {
  d: path("M10 21.5v-3a2 2 0 0 1 4 0v3");
}

:global(.pp7umkmgo) {
  d: path("M3.5 21.5V15L9 12.5V10l3-4l3 4v2.5l5.5 2.5v6.5ZM12 2v4m-2-2.25h4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
