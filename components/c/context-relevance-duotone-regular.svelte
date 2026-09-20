<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vxtvt1e5w"/><path class="qa-jr78us"/><path class="f_3ihgbpt"/><path class="mv4vo2smp"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="nesadtboq"/><path class="mm9i2knor"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:context-relevance-duotone-regular" {...props}></Icon>
<style>
:global(.f_3ihgbpt) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8.5 7H6v6h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ffw_pwyfz) {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

:global(.kfdmhd64i) {
  d: path("m15 15 6 6");
}

:global(.mm9i2knor) {
  d: path("M11.5 7H14v6h-2.5");
}

:global(.mv4vo2smp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11.5 7H14v6h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nesadtboq) {
  d: path("M8.5 7H6v6h2.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qa-jr78us) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vxtvt1e5w) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
