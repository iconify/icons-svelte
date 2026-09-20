<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x6e_qy8ax"/><path class="zey5ebc0a"/><path class="q3srlnbfr"/><path class="c438ceftc"/><path class="l8unaacgj"/><path class="e69i7fcek"/><path class="u363cab-y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gps-lost-duotone-bold" {...props}></Icon>
<style>
:global(.c438ceftc) {
  d: path("M12 17v5");
}

:global(.e69i7fcek) {
  d: path("M17 12h5");
}

:global(.l8unaacgj) {
  d: path("M2 12h5");
}

:global(.q3srlnbfr) {
  d: path("M12 2v5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u363cab-y) {
  d: path("M5 19 19 5");
}

:global(.x6e_qy8ax) {
  fill: currentColor;
  d: path("M7 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zey5ebc0a) {
  d: path("M7 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

</style>
