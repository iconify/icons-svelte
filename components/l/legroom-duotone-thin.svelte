<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mjoku5b6m"/><path class="yzcdzmlnf"/><path class="tmm23ccef"/><path class="tyzts-xze"/><path class="haq4atb7e"/><path class="taxmbub4q"/><path class="q26t8cbjw"/><path class="vg9r0qb2v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:legroom-duotone-thin" {...props}></Icon>
<style>
:global(.haq4atb7e) {
  d: path("M6 2v11h12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mjoku5b6m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 2v11h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q26t8cbjw) {
  d: path("M9 17v3");
}

:global(.taxmbub4q) {
  d: path("M6 17h12");
}

:global(.tmm23ccef) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 17v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tyzts-xze) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 17v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vg9r0qb2v) {
  d: path("M15 17v3");
}

:global(.yzcdzmlnf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
