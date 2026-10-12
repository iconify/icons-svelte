<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dh0sdhbvt"/><path class="jg0aywb6k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:alignment-target-sharp" {...props}></Icon>
<style>
:global(.dh0sdhbvt) {
  d: path("M12 5.5a6.5 6.5 0 1 1 0 13a6.5 6.5 0 1 1 0-13m0-2.75V5.5m0 13v2.75M2.75 12H5.5m13 0h2.75");
}

:global(.jg0aywb6k) {
  d: path("M12 8.5q.42 3.08 3.5 3.5q-3.08.42-3.5 3.5q-.42-3.08-3.5-3.5q3.08-.42 3.5-3.5Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
