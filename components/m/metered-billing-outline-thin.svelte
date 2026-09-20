<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nnzlfsekh"/><path class="teszqoqtj"/><path class="zqsgc7abe"/><path class="rcqkqehsw"/><path class="atlx6nxij"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:metered-billing-outline-thin" {...props}></Icon>
<style>
:global(.atlx6nxij) {
  d: path("m12 13.5 2.5 -2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nnzlfsekh) {
  d: path("M2 8a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.rcqkqehsw) {
  d: path("M8.71 12.3a3.5 3.5 0 0 1 6.58 0");
}

:global(.teszqoqtj) {
  d: path("M5.5 10.5v3");
}

:global(.zqsgc7abe) {
  d: path("M18.5 10.5v3");
}

</style>
