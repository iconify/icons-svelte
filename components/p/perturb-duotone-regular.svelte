<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lbllh8b8w"/><path class="ebxhfjfcu"/><path class="ozi-k-boi"/><path class="ph2id7bdf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:perturb-duotone-regular" {...props}></Icon>
<style>
:global(.ebxhfjfcu) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 15 3 -3 3 3 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lbllh8b8w) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 7h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ozi-k-boi) {
  d: path("M3 7h18");
}

:global(.ph2id7bdf) {
  d: path("m3 15 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

</style>
