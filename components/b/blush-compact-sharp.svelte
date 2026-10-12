<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="whbob806t"/><circle class="gkmarkbih"/><circle class="ivnrysbyn"/><path class="sstohdb_f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:blush-compact-sharp" {...props}></Icon>
<style>
:global(.gkmarkbih) {
  cx: 12px;
  cy: 15.25px;
  r: 6px;
}

:global(.ivnrysbyn) {
  cx: 12px;
  cy: 15.25px;
  r: 3.5px;
}

:global(.sstohdb_f) {
  d: path("M10.25 15.5L12 13.069l1.75 2.431");
}

:global(.whbob806t) {
  d: path("M12 2.75a6 2 0 1 1 0 4a6 2 0 1 1 0-4Zm-2 4v2.5m4-2.5v2.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
