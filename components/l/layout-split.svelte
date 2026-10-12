<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lgmzjf4_y"/><rect class="zbhd3ibvz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:layout-split" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lgmzjf4_y) {
  width: 7.75px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 2px;
}

:global(.zbhd3ibvz) {
  width: 7.75px;
  height: 16.5px;
  x: 13.5px;
  y: 3.75px;
  rx: 2px;
}

</style>
