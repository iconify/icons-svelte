<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v80o62b3w"/><path class="qd2a5rnak"/><path class="sfb1ntbvv"/><path class="zwghjjvbs"/><path class="dapfgct8f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:procedural-memory-duotone-regular" {...props}></Icon>
<style>
:global(.dapfgct8f) {
  d: path("M14 6v10l5 -5Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qd2a5rnak) {
  d: path("M2 6h7");
}

:global(.sfb1ntbvv) {
  d: path("M2 11h7");
}

:global(.v80o62b3w) {
  fill: currentColor;
  d: path("M14 6v10l5 -5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zwghjjvbs) {
  d: path("M2 16h7");
}

</style>
