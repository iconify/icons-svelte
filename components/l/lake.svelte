<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z2pvysbov"/><path class="ckeh6gifg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lake" {...props}></Icon>
<style>
:global(.ckeh6gifg) {
  d: path("M6.75 14.75c.75-.5 1.75-.5 2.5 0s1.75.5 2.5 0m-.75 3c.75-.5 1.75-.5 2.5 0s1.75.5 2.5 0M5.75 9.5l6.25-6l6.25 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z2pvysbov) {
  d: path("M2.75 16.25a9.25 5 0 1 0 18.5 0a9.25 5 0 1 0-18.5 0");
}

</style>
