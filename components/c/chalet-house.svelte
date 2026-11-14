<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rzh7fcbkh"/><path class="mdt0ajbdf"/><path class="ek02avbdz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chalet-house" {...props}></Icon>
<style>
:global(.ek02avbdz) {
  d: path("M10 21v-4.5h4V21");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mdt0ajbdf) {
  d: path("M6 8.5V21h12V8.5");
}

:global(.rzh7fcbkh) {
  d: path("M2.5 12L12 2.5l9.5 9.5");
}

</style>
