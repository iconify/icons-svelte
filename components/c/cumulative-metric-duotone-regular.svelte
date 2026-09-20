<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="h7eqtubzg"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="p80u_bcab"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cumulative-metric-duotone-regular" {...props}></Icon>
<style>
:global(.h7eqtubzg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 17h3v-3h3v-3h3V8h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.iulb4mb6k) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.p80u_bcab) {
  d: path("M7 17h3v-3h3v-3h3V8h3");
}

:global(.pd-i35blz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

</style>
