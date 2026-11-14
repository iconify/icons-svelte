<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ccb46tbsv"/><path class="dkvdnlczs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:crash-free" {...props}></Icon>
<style>
:global(.ccb46tbsv) {
  d: path("m12 2.5l7.5 2.75V11c0 4.5-3 8-7.5 10.5c-4.5-2.5-7.5-6-7.5-10.5V5.25Z");
}

:global(.dkvdnlczs) {
  d: path("m8.5 11.75l2.5 2.5l4.75-5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
