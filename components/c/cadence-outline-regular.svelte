<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pc9haabcx"/><path class="erreycbys"/><path class="syzpzeigb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cadence-outline-regular" {...props}></Icon>
<style>
:global(.erreycbys) {
  d: path("m12 13 5 -5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pc9haabcx) {
  d: path("M5 13a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

:global(.syzpzeigb) {
  d: path("m15 4 5 5");
}

</style>
