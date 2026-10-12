<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="j35vzzkcl"/><path class="xr4p8qxmv"/><circle class="oag1fiv-v"/><path class="f1ejl_brg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:employee-referral-sharp" {...props}></Icon>
<style>
:global(.f1ejl_brg) {
  d: path("M14.25 21.25h-.5v-.5a3.75 3.75 0 0 1 7.5 0v.5h-.5ZM6.5 5.75a7.5 5 0 0 1 11 0m-.43-2.72l.43 2.72l-2.72.43");
}

:global(.j35vzzkcl) {
  cx: 6.5px;
  cy: 11px;
  r: 2.5px;
}

:global(.oag1fiv-v) {
  cx: 17.5px;
  cy: 11px;
  r: 2.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xr4p8qxmv) {
  d: path("M3.25 21.25h-.5v-.5a3.75 3.75 0 0 1 7.5 0v.5h-.5Z");
}

</style>
