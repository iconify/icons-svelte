<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="e0hugac3h"/><path class="e-qrvccol"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:concert-hand-sharp" {...props}></Icon>
<style>
:global(.e-qrvccol) {
  d: path("M9.5 10.5v2.25m2.75-2.25v2.25M15 10.5v2.25M7 14h2.625l1.875-1.5M9 21h6.5");
}

:global(.e0hugac3h) {
  d: path("M7 4.25V3h2.5v7.5H15v-6h2.5v13.75H7v-4.5Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
