<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fjgxau-ai"/><path class="wvokt6bxl"/><path class="o7vhhzbjl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:no-right-turn" {...props}></Icon>
<style>
:global(.fjgxau-ai) {
  d: path("M2.25 12a9.75 9.75 0 1 0 19.5 0a9.75 9.75 0 1 0-19.5 0m3-6.75l13.5 13.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o7vhhzbjl) {
  d: path("M14.5 6.5L17 9l-2.5 2.5");
}

:global(.wvokt6bxl) {
  d: path("M9.5 17.5v-6A2.5 2.5 0 0 1 12 9h5");
}

</style>
