<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="f9xu_cb8q"/><circle class="duo-1eb2o"/><circle class="tbkljbcex"/><path class="w4pmhxuss"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:git-branch-plus-sharp" {...props}></Icon>
<style>
:global(.duo-1eb2o) {
  cx: 6.5px;
  cy: 18.75px;
  r: 2.25px;
}

:global(.f9xu_cb8q) {
  cx: 6.5px;
  cy: 5.25px;
  r: 2.25px;
}

:global(.tbkljbcex) {
  cx: 17.5px;
  cy: 6.75px;
  r: 2.25px;
}

:global(.w4pmhxuss) {
  d: path("M6.5 7.5v9m11-7.5v4.75H10l-3.063-.031L6.5 16.75");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
