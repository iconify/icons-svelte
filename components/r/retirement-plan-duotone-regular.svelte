<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dzw_97oey"/><path class="mp6xg7bgc"/><path class="it6j56pks"/><path class="ojjdplbtx"/><path class="n8uuobb1z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:retirement-plan-duotone-regular" {...props}></Icon>
<style>
:global(.dzw_97oey) {
  fill: currentColor;
  d: path("M3 12a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.it6j56pks) {
  d: path("M6 10V4h12v6");
}

:global(.mp6xg7bgc) {
  d: path("M3 12a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.n8uuobb1z) {
  d: path("M18 18v3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ojjdplbtx) {
  d: path("M6 18v3");
}

</style>
