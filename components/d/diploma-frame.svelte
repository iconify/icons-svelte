<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j24hz-q8l"/><rect class="kxromsfjv"/><path class="fxr7wcrtn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:diploma-frame" {...props}></Icon>
<style>
:global(.fxr7wcrtn) {
  d: path("M8.25 8.25h7.5a1 1 0 0 1 1 1v7.5a1 1 0 0 1-1 1h-7.5a1 1 0 0 1-1-1v-7.5a1 1 0 0 1 1-1m1.5 3.25h4.5m-4.5 3h2.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j24hz-q8l) {
  d: path("m9.5 4.75l2.5-2l2.5 2");
}

:global(.kxromsfjv) {
  width: 16.5px;
  height: 16.5px;
  x: 3.75px;
  y: 4.75px;
  rx: 2px;
}

</style>
