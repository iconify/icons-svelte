<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="x0ulejaqb"/><circle class="ivl5k1bso"/><path class="jpa2tta9t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:halo-ring-sharp" {...props}></Icon>
<style>
:global(.ivl5k1bso) {
  cx: 12px;
  cy: 11px;
  r: 2.75px;
}

:global(.jpa2tta9t) {
  d: path("M4.5 21.25c0-3 3.25-5 7.5-5s7.5 2 7.5 5Z");
}

:global(.x0ulejaqb) {
  d: path("M12 2.75c3.6 0 6.5.67 6.5 1.5s-2.9 1.5-6.5 1.5s-6.5-.67-6.5-1.5s2.9-1.5 6.5-1.5Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
