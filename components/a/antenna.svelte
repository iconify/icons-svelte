<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="kx85uxbfn"/><path class="hcvh8hlqn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:antenna" {...props}></Icon>
<style>
:global(.hcvh8hlqn) {
  d: path("M7.75 21.25L12 8.75l4.25 12.5m-6.75-5h5M8.52 9.69a4.25 4.25 0 0 1 0-4.88m-2.66 6.74a7.5 7.5 0 0 1 0-8.6m9.62 1.86a4.25 4.25 0 0 1 0 4.88m2.66-6.74a7.5 7.5 0 0 1 0 8.6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kx85uxbfn) {
  cx: 12px;
  cy: 7.25px;
  r: 1.5px;
}

</style>
