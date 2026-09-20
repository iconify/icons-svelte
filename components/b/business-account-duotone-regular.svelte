<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wj-e-sbdq"/><path class="mcubrkb2y"/><path class="hco_o0b5n"/><path class="vadimgloz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:business-account-duotone-regular" {...props}></Icon>
<style>
:global(.hco_o0b5n) {
  d: path("M9 14h6v4H9Z");
}

:global(.mcubrkb2y) {
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vadimgloz) {
  d: path("M10 14a2 2 0 0 1 4 0");
}

:global(.wj-e-sbdq) {
  fill: currentColor;
  d: path("M9 14h6v4H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
