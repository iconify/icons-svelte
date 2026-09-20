<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hq7q5pbzv"/><path class="m690iuuio"/><path class="khupvdbel"/><path class="x7qdjyb5k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:corner-left-down-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hq7q5pbzv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 4H10v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.khupvdbel) {
  d: path("M20 4H10v16");
}

:global(.m690iuuio) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 15 5 5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x7qdjyb5k) {
  d: path("m5 15 5 5 5 -5");
}

</style>
