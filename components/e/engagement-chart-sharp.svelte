<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gx1xg5ykg"/><path class="o-k4wluwn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:engagement-chart-sharp" {...props}></Icon>
<style>
:global(.gx1xg5ykg) {
  d: path("M2.75 2.75v18.5h18.5");
}

:global(.o-k4wluwn) {
  d: path("m7 16.5l3.5-3.75l3 2.25l3.25-3.75m.75-1s-3.25-1.9-3.25-4.1a1.6 1.6 0 0 1 3.25-.6a1.6 1.6 0 0 1 3.25.6c0 2.2-3.25 4.1-3.25 4.1Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
