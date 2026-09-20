<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h18rabcld"/><path class="fwgh9qb5h"/><path class="nwn4xu84s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dep-pin-outline-regular" {...props}></Icon>
<style>
:global(.fwgh9qb5h) {
  d: path("M14.5 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.h18rabcld) {
  d: path("M3 5a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nwn4xu84s) {
  d: path("M17.5 14v4.5");
}

</style>
