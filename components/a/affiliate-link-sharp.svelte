<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="mx0ir3bdi"/><circle class="fs3jhybjb"/><path class="mrbssfbyi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:affiliate-link-sharp" {...props}></Icon>
<style>
:global(.fs3jhybjb) {
  cx: 12px;
  cy: 6.75px;
  r: 1.5px;
}

:global(.mrbssfbyi) {
  d: path("M9.25 13.25h-3a2.75 2.75 0 0 0 0 5.5h3m5.5-5.5h3a2.75 2.75 0 0 1 0 5.5h-3M9 16h6");
}

:global(.mx0ir3bdi) {
  cx: 12px;
  cy: 6.75px;
  r: 4px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
