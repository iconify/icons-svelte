<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><circle class="g6ixj6bxw"/><circle class="j87kh1brz"/><path class="npy51_chq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:flushed-face-sharp" {...props}></Icon>
<style>
:global(.dbgvcxwad) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

:global(.g6ixj6bxw) {
  cx: 9px;
  cy: 9.5px;
  r: 1.5px;
}

:global(.j87kh1brz) {
  cx: 15px;
  cy: 9.5px;
  r: 1.5px;
}

:global(.npy51_chq) {
  d: path("M10.75 16.5h2.5m-8-2l1-1.25M7.5 14.5l1-1.25m7 1.25l1-1.25m1.25 1.25l1-1.25");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
