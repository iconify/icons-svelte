<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rh6cspb3h"/><path class="pwvj2zbau"/><path class="gashr7bir"/><path class="jsqnf3b1y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:recycling-day-outline-regular" {...props}></Icon>
<style>
:global(.gashr7bir) {
  d: path("m8 13 3 -3 3 3");
}

:global(.jsqnf3b1y) {
  d: path("m8 17 3 3 3 -3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pwvj2zbau) {
  d: path("M5 8V5h12v3");
}

:global(.rh6cspb3h) {
  d: path("M6 8v13h10V8Z");
}

</style>
