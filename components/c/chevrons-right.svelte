<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kjm_8kbdd"/><path class="x7mmjacnf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chevrons-right" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kjm_8kbdd) {
  d: path("M5.5 5.25L12.25 12L5.5 18.75");
}

:global(.x7mmjacnf) {
  d: path("M11.75 5.25L18.5 12l-6.75 6.75");
}

</style>
