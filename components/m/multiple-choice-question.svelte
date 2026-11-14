<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yd-ecgb4e"/><path class="zcfr36bgf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:multiple-choice-question" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yd-ecgb4e) {
  d: path("M6.5 3.5h11A3.5 3.5 0 0 1 21 7v10a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17V7a3.5 3.5 0 0 1 3.5-3.5");
}

:global(.zcfr36bgf) {
  d: path("M6.25 9a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m0 6a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m5.25-6H17m-5.5 6H17");
}

</style>
