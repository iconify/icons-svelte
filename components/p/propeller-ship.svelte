<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r-3rp7dyv"/><circle class="e-2-i017w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:propeller-ship" {...props}></Icon>
<style>
:global(.e-2-i017w) {
  cx: 12px;
  cy: 12px;
  r: 2.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r-3rp7dyv) {
  d: path("M12 12C5.21.92 18.79.92 12 12m0 0c13-.34 6.2 11.43 0 0m0 0c-6.2 11.43-13-.34 0 0");
}

</style>
