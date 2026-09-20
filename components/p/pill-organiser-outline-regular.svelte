<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oh4p-ccfe"/><path class="rx7vihb0q"/><path class="h7bcztycq"/><path class="k1llj9blt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pill-organiser-outline-regular" {...props}></Icon>
<style>
:global(.h7bcztycq) {
  d: path("M12 8v8");
}

:global(.k1llj9blt) {
  d: path("M17 8v8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oh4p-ccfe) {
  d: path("M2 10a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.rx7vihb0q) {
  d: path("M7 8v8");
}

</style>
