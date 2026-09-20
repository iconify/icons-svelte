<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jzln5b9mk"/><path class="eujto1cse"/><path class="m3i8kpzkt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:counsellor-outline-regular" {...props}></Icon>
<style>
:global(.eujto1cse) {
  d: path("M2.5 18a4.5 4.5 0 0 1 9 0");
}

:global(.jzln5b9mk) {
  d: path("M4 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.m3i8kpzkt) {
  d: path("M13 4h8a1 1 0 0 1 1 1v6a1 1 0 0 1 -1 1h-5l-3 3v-3a1 1 0 0 1 -1 -1V5a1 1 0 0 1 1 -1");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
