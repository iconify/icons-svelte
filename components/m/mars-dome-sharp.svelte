<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="c03w2lbvk"/><path class="tv40p4b1r"/><circle class="zgosk9b6o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mars-dome-sharp" {...props}></Icon>
<style>
:global(.c03w2lbvk) {
  d: path("M2.75 20.5a9.25 9.25 0 0 1 18.5 0Z");
}

:global(.tv40p4b1r) {
  d: path("M4 16h16M7.25 20.5L9.5 16l2.5-4.75L14.5 16l2.25 4.5M9.5 16h5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zgosk9b6o) {
  cx: 17.75px;
  cy: 5.25px;
  r: 2.5px;
}

</style>
