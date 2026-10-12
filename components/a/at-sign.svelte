<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="m10ymsugb"/><path class="p9cw2vbot"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:at-sign" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m10ymsugb) {
  cx: 12px;
  cy: 12px;
  r: 3.5px;
}

:global(.p9cw2vbot) {
  d: path("M15.5 8.5v4.75a2.5 2.5 0 0 0 5 0V12a8.5 8.5 0 1 0-3.75 7.05");
}

</style>
