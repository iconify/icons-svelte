<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gswzab2hg"/><circle class="nj-qotb6t"/><circle class="y2w0_hbmh"/><circle class="macqmobic"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:list-bullet-sharp" {...props}></Icon>
<style>
:global(.gswzab2hg) {
  d: path("M9.75 5.5h10.5M9.75 12h10.5m-10.5 6.5h10.5");
}

:global(.macqmobic) {
  cx: 5px;
  cy: 18.5px;
  r: 1.5px;
}

:global(.nj-qotb6t) {
  cx: 5px;
  cy: 5.5px;
  r: 1.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y2w0_hbmh) {
  cx: 5px;
  cy: 12px;
  r: 1.5px;
}

</style>
