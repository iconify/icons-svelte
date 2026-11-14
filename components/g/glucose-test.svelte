<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fshtepbwx"/><path class="ulbgdr79k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:glucose-test" {...props}></Icon>
<style>
:global(.fshtepbwx) {
  d: path("M7.5 21.5V17a4.5 4.5 0 0 1 9 0v4.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ulbgdr79k) {
  fill: currentColor;
  d: path("m12 3l2.25 3a2.5 2.5 0 1 1-4.5 0Z");
}

</style>
