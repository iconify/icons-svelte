<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ebdii9bub"/><circle class="ygphxfbhc"/><path class="vyhli1bqq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:load-shedding-sharp" {...props}></Icon>
<style>
:global(.ebdii9bub) {
  d: path("m11.5 3l-5 8h6L8 19");
}

:global(.vyhli1bqq) {
  d: path("M17.25 15.25v2l1.5 1");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ygphxfbhc) {
  cx: 17.25px;
  cy: 17.25px;
  r: 4px;
}

</style>
