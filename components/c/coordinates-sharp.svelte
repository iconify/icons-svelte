<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><path class="adh0_h19v"/><circle class="xv5udabog"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:coordinates-sharp" {...props}></Icon>
<style>
:global(.adh0_h19v) {
  d: path("M3.17 9.25H13m4 0h3.83m-5.83-6v4m0 4v9.5");
}

:global(.dbgvcxwad) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xv5udabog) {
  cx: 15px;
  cy: 9.25px;
  r: 2px;
}

</style>
