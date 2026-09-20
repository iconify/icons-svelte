<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mg7aqnbsf"/><path class="rtofn9dtv"/><path class="b26q0zi5z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:align-start-horizontal-outline-regular" {...props}></Icon>
<style>
:global(.b26q0zi5z) {
  d: path("M14 7h4v6h-4Z");
}

:global(.mg7aqnbsf) {
  d: path("M3 4h18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rtofn9dtv) {
  d: path("M7 7h4v10H7Z");
}

</style>
