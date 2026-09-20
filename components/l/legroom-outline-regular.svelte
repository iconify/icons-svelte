<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="haq4atb7e"/><path class="taxmbub4q"/><path class="q26t8cbjw"/><path class="vg9r0qb2v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:legroom-outline-regular" {...props}></Icon>
<style>
:global(.haq4atb7e) {
  d: path("M6 2v11h12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q26t8cbjw) {
  d: path("M9 17v3");
}

:global(.taxmbub4q) {
  d: path("M6 17h12");
}

:global(.vg9r0qb2v) {
  d: path("M15 17v3");
}

</style>
