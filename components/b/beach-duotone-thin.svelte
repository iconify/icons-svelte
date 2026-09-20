<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tcg6nubhf"/><path class="ke8s6xb3g"/><path class="evcx__bzi"/><path class="tee5ti87r"/><path class="nqnw98byf"/><path class="olqfcgidt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:beach-duotone-thin" {...props}></Icon>
<style>
:global(.evcx__bzi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 19h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ke8s6xb3g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 14h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nqnw98byf) {
  d: path("M2 14h20");
}

:global(.olqfcgidt) {
  d: path("M6 19h12");
}

:global(.tcg6nubhf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 9 3 -3 3 3 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tee5ti87r) {
  d: path("m3 9 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

</style>
