<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rh6cspb3h"/><path class="pwvj2zbau"/><path class="gashr7bir"/><path class="jsqnf3b1y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:recycling-day-outline-bold" {...props}></Icon>
<style>
:global(.gashr7bir) {
  d: path("m8 13 3 -3 3 3");
}

:global(.jsqnf3b1y) {
  d: path("m8 17 3 3 3 -3");
}

:global(.pwvj2zbau) {
  d: path("M5 8V5h12v3");
}

:global(.rh6cspb3h) {
  d: path("M6 8v13h10V8Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
