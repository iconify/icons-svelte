<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cwmo4bc4s"/><path class="m5wi144di"/><path class="nk1txyodw"/><path class="o7fu1nbtq"/><path class="eus9a2f4d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:lifecycle-rule-outline-regular" {...props}></Icon>
<style>
:global(.cwmo4bc4s) {
  d: path("M3 5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2");
}

:global(.eus9a2f4d) {
  d: path("M16.5 12.5 19 15l2.5 -2.5");
}

:global(.m5wi144di) {
  d: path("M3 12a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2");
}

:global(.nk1txyodw) {
  d: path("M3 19a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o7fu1nbtq) {
  d: path("M19 5v10");
}

</style>
