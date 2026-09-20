<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h68oqyb7w"/><path class="yk4p0gbnv"/><path class="wmesk9jct"/><path class="eb8112kbp"/><path class="c7dgfu7wx"/><path class="m46vgkb_g"/><path class="fk1mncnjn"/><path class="xogm81bqq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:backstage-duotone-bold" {...props}></Icon>
<style>
:global(.c7dgfu7wx) {
  d: path("M2 4h20");
}

:global(.eb8112kbp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 21v-9h4v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fk1mncnjn) {
  d: path("M21 4v17h-2.5C17 21 17 20 17 18V4");
}

:global(.h68oqyb7w) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 4h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m46vgkb_g) {
  d: path("M3 4v17h2.5C7 21 7 20 7 18V4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wmesk9jct) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 4v17h-2.5C17 21 17 20 17 18V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xogm81bqq) {
  d: path("M10 21v-9h4v9");
}

:global(.yk4p0gbnv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 4v17h2.5C7 21 7 20 7 18V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
