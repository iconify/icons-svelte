<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rbbg71bnu"/><path class="nu_hw4iyy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pen-display" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nu_hw4iyy) {
  d: path("m7.5 16.75l-1.75 4.5m10.75-4.5l1.75 4.5M9 12.75l6.25-6.25");
}

:global(.rbbg71bnu) {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 3.25px;
  rx: 2.5px;
}

</style>
