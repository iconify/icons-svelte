<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="giuwvvbzw"/><path class="m2n06fbwx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ecg-paper" {...props}></Icon>
<style>
:global(.giuwvvbzw) {
  d: path("M3 5h18v12l-2 2l-2-2l-2 2l-2-2l-2 2l-2-2l-2 2l-2-2l-2 2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m2n06fbwx) {
  d: path("M5.5 11.5h3l1.5-3l2 5.5l1.5-4l1 1.5h4");
}

</style>
