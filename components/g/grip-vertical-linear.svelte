<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="rhe-p1bon"/><circle class="ljb84cuaz"/><circle class="out3f_12j"/><circle class="ov9m4obnk"/><circle class="r41_wgb9w"/><circle class="lqrlnfbtg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:grip-vertical-linear" {...props}></Icon>
<style>
:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ljb84cuaz) {
  cx: 15.512px;
  cy: 12px;
  r: 0.75px;
}

:global(.lqrlnfbtg) {
  cx: 8.488px;
  cy: 5px;
  r: 0.75px;
}

:global(.out3f_12j) {
  cx: 15.496px;
  cy: 5px;
  r: 0.75px;
}

:global(.ov9m4obnk) {
  cx: 8.504px;
  cy: 19px;
  r: 0.75px;
}

:global(.r41_wgb9w) {
  cx: 8.504px;
  cy: 12px;
  r: 0.75px;
}

:global(.rhe-p1bon) {
  cx: 15.512px;
  cy: 19px;
  r: 0.75px;
}

</style>
