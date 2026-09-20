<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tchcdobrl"/><path class="f114hzb2m"/><path class="awnenfb8l"/><path class="k00r0bcel"/><path class="x4bni5twb"/><path class="p8u061b4s"/><path class="nhri7pb9i"/><path class="gsl5knvuq"/><path class="xa52mrrsy"/><path class="e5d_yrbyo"/><path class="z82iob5ig"/><path class="q9naw_b2m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mist-duotone-bold" {...props}></Icon>
<style>
:global(.awnenfb8l) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 13h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e5d_yrbyo) {
  d: path("M12 13h9");
}

:global(.f114hzb2m) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 8h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gsl5knvuq) {
  d: path("M15 8h6");
}

:global(.k00r0bcel) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 13h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nhri7pb9i) {
  d: path("M3 8h9");
}

:global(.p8u061b4s) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q9naw_b2m) {
  d: path("M17 18h4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tchcdobrl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 8h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x4bni5twb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 18h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xa52mrrsy) {
  d: path("M3 13h6");
}

:global(.z82iob5ig) {
  d: path("M5 18h9");
}

</style>
