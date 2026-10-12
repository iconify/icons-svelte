<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vf_31rbpy"/><path class="e33y3ef2i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chart-forecast-sharp" {...props}></Icon>
<style>
:global(.e33y3ef2i) {
  d: path("m7.25 16.25l3.5-4l2.5 2m1-1.15l1.25-1.5m1-1.15l1.25-1.5m1-1.2L20 6.25");
}

:global(.vf_31rbpy) {
  d: path("M3.75 3.75v16.5h16.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
