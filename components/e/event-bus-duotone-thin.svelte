<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="px1u_4qiq"/><path class="p24r95ukg"/><path class="sc-gdybyv"/><path class="h3piw-bad"/><path class="x26a8iq1c"/><path class="ugztwkaee"/><path class="j-bg0m85s"/><path class="th8j40bfn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:event-bus-duotone-thin" {...props}></Icon>
<style>
:global(.h3piw-bad) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 5v4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j-bg0m85s) {
  d: path("M12 14.5V19");
}

:global(.p24r95ukg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 5v4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.px1u_4qiq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sc-gdybyv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 14.5V19");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.th8j40bfn) {
  d: path("M18 5v4.5");
}

:global(.ugztwkaee) {
  d: path("M6 5v4.5");
}

:global(.x26a8iq1c) {
  d: path("M2 12h20");
}

</style>
