<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ql2kcqmht"/><circle class="drobnoznw"/><circle class="em4k7_b5o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bicycle-sharp" {...props}></Icon>
<style>
:global(.drobnoznw) {
  cx: 5.5px;
  cy: 17px;
  r: 2.75px;
}

:global(.em4k7_b5o) {
  cx: 18.5px;
  cy: 17px;
  r: 2.75px;
}

:global(.ql2kcqmht) {
  d: path("M8.25 17H11L9.6 9.25m-1.35 0H11m-.95 2.5h6.59M11 17l5.2-6.5m-.7-2l2.08 5.91M15.5 8.5H19v2.25");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
