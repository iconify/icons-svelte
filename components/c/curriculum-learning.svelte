<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fou38nr4y"/><path class="y_lgkdbvx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:curriculum-learning" {...props}></Icon>
<style>
:global(.fou38nr4y) {
  d: path("M2.5 20.5h19v-9H17v3H9.5v3h-7Zm13-10.5V5.5A1.5 1.5 0 0 1 17 4h4.5v7.5H17a1.5 1.5 0 0 1-1.5-1.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y_lgkdbvx) {
  d: path("M15.5 10A1.5 1.5 0 0 1 17 8.5h4.5");
}

</style>
