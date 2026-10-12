<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="q71tojf4b"/><path class="zs3o2ob7q"/><circle class="se8pm3_-l"/><path class="dxcm-ab6w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:map-pin-flag-sharp" {...props}></Icon>
<style>
:global(.dxcm-ab6w) {
  d: path("M8.5 21h7");
}

:global(.q71tojf4b) {
  cx: 12px;
  cy: 8.25px;
  r: 5.5px;
}

:global(.se8pm3_-l) {
  cx: 12px;
  cy: 8.25px;
  r: 2px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zs3o2ob7q) {
  d: path("M12 13.75v4.75");
}

</style>
