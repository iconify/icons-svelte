<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="emyboub8n"/><path class="tbe304aqf"/><path class="ezum2i4ey"/><path class="rwjci8tle"/><path class="ng35sb6yg"/><path class="ys-dg812g"/><path class="dv6re0b-t"/><path class="ogqckebrf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:recovery-score-duotone-regular" {...props}></Icon>
<style>
:global(.dv6re0b-t) {
  d: path("M12 16V8");
}

:global(.emyboub8n) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ezum2i4ey) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 16V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ng35sb6yg) {
  d: path("M3 16a9 9 0 0 1 18 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ogqckebrf) {
  d: path("m9 11 3 -3 3 3");
}

:global(.rwjci8tle) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 11 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tbe304aqf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ys-dg812g) {
  d: path("M3 16h18");
}

</style>
