<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="igd1_mbip"/><circle class="pgksv8bwe"/><path class="qffcw0b3k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:gpu-card-sharp" {...props}></Icon>
<style>
:global(.igd1_mbip) {
  d: path("M2.75 4.75v14.5m3-13.5h15.5v10.5H5.75z");
}

:global(.pgksv8bwe) {
  cx: 10.25px;
  cy: 11px;
  r: 2px;
}

:global(.qffcw0b3k) {
  d: path("M16.75 9a2 2 0 1 1 0 4a2 2 0 1 1 0-4m-8 7.25v3h7v-3");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
