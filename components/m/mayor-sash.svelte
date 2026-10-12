<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="mx0ir3bdi"/><path class="dv7i_bc8i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mayor-sash" {...props}></Icon>
<style>
:global(.dv7i_bc8i) {
  d: path("M4.25 21.25a7.75 7.75 0 0 1 15.5 0Zm3.5-6.75l6.75 6.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mx0ir3bdi) {
  cx: 12px;
  cy: 6.75px;
  r: 4px;
}

</style>
