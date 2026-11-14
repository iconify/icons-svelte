<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uabevdgnf"/><path class="eg34zmbzq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lawn-chair" {...props}></Icon>
<style>
:global(.eg34zmbzq) {
  d: path("M6 8h9v5m-7 0l9 8m0-8l-9 8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uabevdgnf) {
  d: path("m4.75 3l2.5 10H18.5");
}

</style>
