<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h033mmb1s"/><path class="ljo-5rbrq"/><path class="c9ozk5b7o"/><path class="cgtt6abkv"/><path class="c7dgfu7wx"/><path class="n-z4jv76k"/><path class="qagp93bmg"/><path class="diaqyhfcp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:darkroom-duotone-thin" {...props}></Icon>
<style>
:global(.c7dgfu7wx) {
  d: path("M2 4h20");
}

:global(.c9ozk5b7o) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 4v14h10V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cgtt6abkv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 14 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.diaqyhfcp) {
  d: path("M10 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.h033mmb1s) {
  fill: currentColor;
  d: path("M10 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ljo-5rbrq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 4h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n-z4jv76k) {
  d: path("M7 4v14h10V4");
}

:global(.qagp93bmg) {
  d: path("m9 14 3 -3 3 3");
}

</style>
