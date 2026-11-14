<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uchj1tp-v"/><path class="imqocpb3g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bamboo" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.imqocpb3g) {
  d: path("M10 9q5-.5 8 3q-5 1-8-3M5.5 9H10m-4.5 6.5H10");
}

:global(.uchj1tp-v) {
  d: path("M7.25 2.5h1A1.75 1.75 0 0 1 10 4.25v15.5a1.75 1.75 0 0 1-1.75 1.75h-1a1.75 1.75 0 0 1-1.75-1.75V4.25A1.75 1.75 0 0 1 7.25 2.5M10 9q3-4.5 8.5-4.5Q15.5 9 10 9");
}

</style>
