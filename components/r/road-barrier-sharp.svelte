<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vkm9fxcym"/><circle class="ggsmnab5p"/><path class="sum-9ccvt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:road-barrier-sharp" {...props}></Icon>
<style>
:global(.ggsmnab5p) {
  cx: 6px;
  cy: 4px;
  r: 1.25px;
}

:global(.sum-9ccvt) {
  d: path("M6 5.25V8m-1.5 4l4 9.25m0-9.25l-4 9.25m11-9.25l4 9.25m0-9.25l-4 9.25");
}

:global(.vkm9fxcym) {
  d: path("M2.75 8h18.5v4H2.75zm4.75 4L10 8m3.5 4L16 8");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
