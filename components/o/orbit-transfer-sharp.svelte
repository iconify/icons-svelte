<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="peiq2hfxm"/><path class="cq61gq66i"/><path class="w526dfbhz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:orbit-transfer-sharp" {...props}></Icon>
<style>
:global(.cq61gq66i) {
  d: path("M16.5 12a4.5 4.5 0 1 0-7.68 3.18");
}

:global(.peiq2hfxm) {
  cx: 12px;
  cy: 12px;
  r: 1.75px;
}

:global(.w526dfbhz) {
  d: path("M3.31 8.84a9.25 9.25 0 0 1 17.38 0M16.5 12a6.875 6.45 0 0 1-13.75 0");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
