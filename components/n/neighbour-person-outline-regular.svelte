<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aj1uncbqw"/><path class="mddrthmzf"/><path class="nr6agbx1r"/><path class="yo0q-4dzc"/><path class="uc661cbro"/><path class="yafg6v4zg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:neighbour-person-outline-regular" {...props}></Icon>
<style>
:global(.aj1uncbqw) {
  d: path("M4 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.mddrthmzf) {
  d: path("M3 16a4 4 0 0 1 8 0");
}

:global(.nr6agbx1r) {
  d: path("M15 6v14");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uc661cbro) {
  d: path("M15 10h4");
}

:global(.yafg6v4zg) {
  d: path("M15 15h4");
}

:global(.yo0q-4dzc) {
  d: path("M19 6v14");
}

</style>
