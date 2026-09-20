<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bv1y61bvs"/><path class="ils7yp4cg"/><path class="v2r_pnsln"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:all-inclusive-outline-thin" {...props}></Icon>
<style>
:global(.bv1y61bvs) {
  d: path("M4 16a8 8 0 0 1 16 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ils7yp4cg) {
  d: path("M2 16h20");
}

:global(.v2r_pnsln) {
  d: path("m8 9 3 3 5 -5");
}

</style>
