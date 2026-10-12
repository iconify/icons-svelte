<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="et_xc3zja"/><path class="y6fd6lbzh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:power-off-eco" {...props}></Icon>
<style>
:global(.et_xc3zja) {
  d: path("M6.5 7.25a8 8 0 1 0 11 0M12 2.75v7.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y6fd6lbzh) {
  d: path("M9.25 17.25c.25-2.8 1.65-4 5.5-4c-.25 2.8-1.65 4-5.5 4");
}

</style>
