<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v7p687byl"/><path class="m44w6yf_n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flight-boarding-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m44w6yf_n) {
  d: path("m12 2 2.5 2.5v5L21 16h-6.5v3l2.5 2.5H7L9.5 19v-3H3l6.5 -6.5v-5Z");
}

:global(.v7p687byl) {
  fill: currentColor;
  d: path("m12 2 2.5 2.5v5L21 16h-6.5v3l2.5 2.5H7L9.5 19v-3H3l6.5 -6.5v-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
