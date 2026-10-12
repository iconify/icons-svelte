<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="os95oubfs"/><path class="opwpyis2y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hazard-lights-sharp" {...props}></Icon>
<style>
:global(.opwpyis2y) {
  d: path("m12.49 10.12l3.27 5.76l.49.87h-8.5l.49-.87l3.27-5.76l.49-.87z");
}

:global(.os95oubfs) {
  d: path("M12.97 4.75L20.28 18l.97 1.75H2.75L3.72 18l7.31-13.25L12 3z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
