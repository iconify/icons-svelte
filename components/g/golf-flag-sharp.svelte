<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="k3kt6vuqp"/><circle class="fx05sjbwb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:golf-flag-sharp" {...props}></Icon>
<style>
:global(.fx05sjbwb) {
  cx: 18.5px;
  cy: 18.25px;
  r: 1.75px;
}

:global(.k3kt6vuqp) {
  d: path("M9 18.25v-15m.68.31l5.89 2.63l.68.31l-.68.31l-5.89 2.63l-.68.31v-6.5zM3.25 18.25C3.25 17.01 5.82 16 9 16s5.75 1.01 5.75 2.25S12.18 20.5 9 20.5s-5.75-1.01-5.75-2.25Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
