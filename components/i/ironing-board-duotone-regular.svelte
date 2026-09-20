<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l1-bc96bi"/><path class="bu8ore6lj"/><path class="hwh3wzbtm"/><path class="f6o19s4sp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ironing-board-duotone-regular" {...props}></Icon>
<style>
:global(.bu8ore6lj) {
  d: path("M3 6h14a3 3 0 0 1 0 6H3Z");
}

:global(.f6o19s4sp) {
  d: path("M13 12c1 3 2 6 3 8");
}

:global(.hwh3wzbtm) {
  d: path("M7 12c-1 3 -2 6 -3 8");
}

:global(.l1-bc96bi) {
  fill: currentColor;
  d: path("M3 6h14a3 3 0 0 1 0 6H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
