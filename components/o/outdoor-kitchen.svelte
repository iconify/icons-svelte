<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ufa9yivum"/><path class="p_taqacgq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:outdoor-kitchen" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p_taqacgq) {
  d: path("M15 9.25V3.5h3v8M2.5 17h19M5 17v4.5M19 17v4.5M8.5 17v-2.5a3.5 3.5 0 0 1 7 0V17");
}

:global(.ufa9yivum) {
  d: path("M4 17a8 8.5 0 0 1 16 0");
}

</style>
