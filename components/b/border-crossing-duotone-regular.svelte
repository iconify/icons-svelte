<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zrbvwbtjz"/><path class="jpdmbcfrc"/><path class="i9n3fxbli"/><path class="sdfde2c8d"/><path class="bgjpknbib"/><path class="q3srlnbfr"/><path class="mxzk029nb"/><path class="c438ceftc"/><path class="n96aj2bbi"/><path class="zpl29uvhf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:border-crossing-duotone-regular" {...props}></Icon>
<style>
:global(.bgjpknbib) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c438ceftc) {
  d: path("M12 17v5");
}

:global(.i9n3fxbli) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 17v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jpdmbcfrc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 10v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mxzk029nb) {
  d: path("M12 10v4");
}

:global(.n96aj2bbi) {
  d: path("M4 12h15");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q3srlnbfr) {
  d: path("M12 2v5");
}

:global(.sdfde2c8d) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 12h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zpl29uvhf) {
  d: path("m16 9 3 3 -3 3");
}

:global(.zrbvwbtjz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 2v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
