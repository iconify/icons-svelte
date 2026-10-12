<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rui-a3b0o"/><path class="vtal1uetk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:heading-4-sharp" {...props}></Icon>
<style>
:global(.rui-a3b0o) {
  d: path("M3 4.75v14.5m5.75-14.5v14.5M3 12h5.75m3-4.75h9.5v12h-9.5z");
}

:global(.vtal1uetk) {
  d: path("M17.5 16.75V10L14 14.75h5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
