<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="p95o4hbbt"/><path class="j985bibko"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:package-keep-dry-sharp" {...props}></Icon>
<style>
:global(.j985bibko) {
  d: path("M6.5 12a5.5 5.5 0 0 1 11 0Zm5.5 0v5.5H9.5v-1.25");
}

:global(.p95o4hbbt) {
  d: path("M2.75 3.75h18.5v17.5H2.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
