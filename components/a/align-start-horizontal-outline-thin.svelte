<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mg7aqnbsf"/><path class="rtofn9dtv"/><path class="b26q0zi5z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:align-start-horizontal-outline-thin" {...props}></Icon>
<style>
:global(.b26q0zi5z) {
  d: path("M14 7h4v6h-4Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mg7aqnbsf) {
  d: path("M3 4h18");
}

:global(.rtofn9dtv) {
  d: path("M7 7h4v10H7Z");
}

</style>
