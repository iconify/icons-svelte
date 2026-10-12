<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nv_f5nmbe"/><circle class="phxq_-r2r"/><circle class="qp-tl-83e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:combine-harvester-sharp" {...props}></Icon>
<style>
:global(.nv_f5nmbe) {
  d: path("M8 12V2.75h5.5V7H20v5h-1Zm2.25-7h1m-8.5 4H5.5v6H2.75zm2.75 2H8m10-4l3.25-3.25");
}

:global(.phxq_-r2r) {
  cx: 11px;
  cy: 18.25px;
  r: 3px;
}

:global(.qp-tl-83e) {
  cx: 19px;
  cy: 19.25px;
  r: 2px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
