<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zf0hjabqk"/><path class="wf0166biv"/><path class="fyvuwdboc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hand-holding-coin-stack" {...props}></Icon>
<style>
:global(.fyvuwdboc) {
  d: path("M8.5 8.5a4.5 2 0 0 0 9 0m-15 7H6L9.5 17H19a1.75 1.75 0 0 1 0 3.5l-7 1H2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wf0166biv) {
  d: path("M8.5 4.75V12a4.5 2 0 0 0 9 0V4.75");
}

:global(.zf0hjabqk) {
  d: path("M8.5 4.75a4.5 2 0 1 0 9 0a4.5 2 0 1 0-9 0");
}

</style>
