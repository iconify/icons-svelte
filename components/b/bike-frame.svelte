<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="utn92pbbn"/><path class="tfzes5u-q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bike-frame" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tfzes5u-q) {
  d: path("M9 8.5h8l.75 3l-6.75 6m6.75-6l3.25 6m-12-9l-.5-3m-2 0h4m6.5 3l-.5-3h3");
}

:global(.utn92pbbn) {
  d: path("M3 17.5h8l-2-9Z");
}

</style>
