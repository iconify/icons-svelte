<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="rzyzgqcqn"/><path class="lqmqmxptf"/><circle class="nvay6mg0g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:orbit-path" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lqmqmxptf) {
  d: path("M19.58 9.13a9.25 5 0 1 1-6.77-2.11");
}

:global(.nvay6mg0g) {
  cx: 16.63px;
  cy: 7.67px;
  r: 2px;
}

:global(.rzyzgqcqn) {
  cx: 12px;
  cy: 12px;
  r: 2.25px;
}

</style>
