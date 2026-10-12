<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="itt9800jv"/><path class="vzp106bxz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:christmas-stocking" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.itt9800jv) {
  width: 9px;
  height: 3.5px;
  x: 7px;
  y: 2.75px;
  rx: 1px;
}

:global(.vzp106bxz) {
  d: path("M9.5 6.25h4q1.5 0 1.5 1.5v4q0 1.5 1.21 2.39l2.33 1.72q1.21.89.33 2.11l-1.49 2.06q-.88 1.22-2.09.33l-6.08-4.47Q8 15 8 13.5V7.75q0-1.5 1.5-1.5");
}

</style>
