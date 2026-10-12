<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vkj93pbwb"/><circle class="hvgdv64iz"/><path class="z32e36b5m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ai-cost-meter-sharp" {...props}></Icon>
<style>
:global(.hvgdv64iz) {
  cx: 12px;
  cy: 13px;
  r: 1.75px;
}

:global(.vkj93pbwb) {
  d: path("M3.75 13a8.25 8.25 0 0 1 16.5 0m-7.18-1.38L15.5 8.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z32e36b5m) {
  d: path("M5.75 17.25h12.5v4H5.75z");
}

</style>
