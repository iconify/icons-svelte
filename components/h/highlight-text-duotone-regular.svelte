<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zyr0_hpav"/><path class="rt55a5byn"/><path class="y4_6s7b5v"/><path class="tu0fdo1xi"/><path class="ju4i6gx3w"/><path class="n8sqmebht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:highlight-text-duotone-regular" {...props}></Icon>
<style>
:global(.ju4i6gx3w) {
  d: path("M7 11h10v3H7Z");
}

:global(.n8sqmebht) {
  d: path("M7 18h10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rt55a5byn) {
  fill: currentColor;
  d: path("M7 11h10v3H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.tu0fdo1xi) {
  d: path("M7 7h10");
}

:global(.y4_6s7b5v) {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.zyr0_hpav) {
  fill: currentColor;
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
