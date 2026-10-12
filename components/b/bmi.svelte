<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="w0dy7ackv"/><path class="r34d66ayj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bmi" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r34d66ayj) {
  d: path("M8.75 21.25V17.5a3.25 3.25 0 0 1 6.5 0v3.75Zm-6-6.25a9.25 9.25 0 0 1 3.06-6.87m2.72-1.71a9.25 9.25 0 0 1 6.94 0m2.72 1.71A9.25 9.25 0 0 1 21.25 15");
}

:global(.w0dy7ackv) {
  cx: 12px;
  cy: 10.5px;
  r: 1.5px;
}

</style>
