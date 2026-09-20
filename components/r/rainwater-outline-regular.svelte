<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="opskey5wx"/><path class="y07a50u1t"/><path class="ctb0q1bmb"/><path class="f1_59klhv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rainwater-outline-regular" {...props}></Icon>
<style>
:global(.ctb0q1bmb) {
  d: path("m9 5 2 2a2 2 0 0 1 -4 0Z");
}

:global(.f1_59klhv) {
  d: path("m15 4 2 2a2 2 0 0 1 -4 0Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.opskey5wx) {
  d: path("M7 13v7h10v-7");
}

:global(.y07a50u1t) {
  d: path("M5 13h14");
}

</style>
