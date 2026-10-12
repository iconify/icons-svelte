<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="k7v5uwbhc"/><rect class="l_han5bst"/><path class="o-5_s5npo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:axle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k7v5uwbhc) {
  width: 4px;
  height: 14.5px;
  x: 2.75px;
  y: 4.75px;
  rx: 1.5px;
}

:global(.l_han5bst) {
  width: 4px;
  height: 14.5px;
  x: 17.25px;
  y: 4.75px;
  rx: 1.5px;
}

:global(.o-5_s5npo) {
  d: path("M2.75 9h4m-4 6h4m10.5-6h4m-4 6h4m-14.5-3h10.5");
}

</style>
