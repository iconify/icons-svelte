<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="apgased_o"/><path class="c18pc1bgs"/><path class="b365s8b3f"/><path class="x70eewbnr"/><path class="cmz4hzb5r"/><path class="r-k_ekbaq"/><path class="f9t4wkbqv"/><path class="ugh4qacil"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:error-handler-duotone-regular" {...props}></Icon>
<style>
:global(.apgased_o) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 12h6l4 -4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.b365s8b3f) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m19 14 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c18pc1bgs) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 12 4 4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cmz4hzb5r) {
  d: path("M2 12h6l4 -4h5");
}

:global(.f9t4wkbqv) {
  d: path("m19 14 3 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r-k_ekbaq) {
  d: path("m8 12 4 4h5");
}

:global(.ugh4qacil) {
  d: path("m22 14 -3 3");
}

:global(.x70eewbnr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m22 14 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
