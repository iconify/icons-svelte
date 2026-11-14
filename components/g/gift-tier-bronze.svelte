<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zkks6er1t"/><path class="kaeh4oboj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gift-tier-bronze" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kaeh4oboj) {
  d: path("M5 7.75v2a7 3 0 0 0 14 0v-2M2.5 19.5h19M5 19.5v-4h14v4");
}

:global(.zkks6er1t) {
  d: path("M5 7.75a7 3 0 1 0 14 0a7 3 0 1 0-14 0");
}

</style>
