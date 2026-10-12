<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ons53cb4g"/><path class="m1awmpdbo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:live-dot-sharp" {...props}></Icon>
<style>
:global(.m1awmpdbo) {
  d: path("M8.5 8.5a4.83 4.83 0 0 0 0 7m7-7a4.83 4.83 0 0 1 0 7M5.25 5.75a9.06 9.06 0 0 0 0 12.5m13.5-12.5a9.06 9.06 0 0 1 0 12.5");
}

:global(.ons53cb4g) {
  cx: 12px;
  cy: 12px;
  r: 2.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
