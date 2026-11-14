<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p5ci-jblb"/><path class="wbjzxcbfx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:publisher" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p5ci-jblb) {
  d: path("m7.5 6.5l3.529-2.353a1.75 1.75 0 0 1 1.942 0L16.5 6.5a1.638 1.638 0 0 1-.908 3H8.408a1.638 1.638 0 0 1-.908-3M4 9.5V21h16V9.5");
}

:global(.wbjzxcbfx) {
  d: path("M12 13.5c-1.5-1-3.5-1.25-4.5-1V17c1-.25 3 0 4.5 1c1.5-1 3.5-1.25 4.5-1v-4.5c-1-.25-3 0-4.5 1m0 0V18");
}

</style>
