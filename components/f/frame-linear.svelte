<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="raqzb_bqt"/><path class="beu8enohc"/><path class="uzjzslbbw"/><path class="oqpf2r_po"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:frame-linear" {...props}></Icon>
<style>
:global(.beu8enohc) {
  d: path("M22 19H2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oqpf2r_po) {
  d: path("M5 22L5 2");
}

:global(.raqzb_bqt) {
  d: path("M22 5H2");
}

:global(.uzjzslbbw) {
  d: path("M19 22L19 2");
}

</style>
