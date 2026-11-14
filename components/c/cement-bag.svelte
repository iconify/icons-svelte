<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g2gw_vjmn"/><path class="xpi4w_nzx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cement-bag" {...props}></Icon>
<style>
:global(.g2gw_vjmn) {
  d: path("M5.5 6.5h13l1 13.5a1.5 1.5 0 0 1-1.5 1.5H6A1.5 1.5 0 0 1 4.5 20Zm0 0l1.5-4h10l1.5 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xpi4w_nzx) {
  d: path("M9.75 11h4.5A1.75 1.75 0 0 1 16 12.75v1.5A1.75 1.75 0 0 1 14.25 16h-4.5A1.75 1.75 0 0 1 8 14.25v-1.5A1.75 1.75 0 0 1 9.75 11");
}

</style>
