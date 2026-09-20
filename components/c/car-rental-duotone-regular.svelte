<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qp882rbfj"/><path class="h03wmtogt"/><path class="yo-dkgbus"/><path class="qt24fkw_c"/><path class="sqwju3bsh"/><path class="du3agkbjb"/><path class="fquh7rbnp"/><path class="v6j2lm37i"/><path class="jqdaf4bpj"/><path class="m2vc0klek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:car-rental-duotone-regular" {...props}></Icon>
<style>
:global(.du3agkbjb) {
  d: path("M5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.fquh7rbnp) {
  d: path("M15 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.h03wmtogt) {
  fill: currentColor;
  d: path("M5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.jqdaf4bpj) {
  d: path("M12 9.5v3");
}

:global(.m2vc0klek) {
  d: path("M12 12.5h2.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qp882rbfj) {
  fill: currentColor;
  d: path("M2 16V8.5h4L9.5 5h5L18 8.5h4V16Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.qt24fkw_c) {
  fill: currentColor;
  d: path("M9 12.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.sqwju3bsh) {
  d: path("M2 16V8.5h4L9.5 5h5L18 8.5h4V16Z");
}

:global(.v6j2lm37i) {
  d: path("M9 12.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.yo-dkgbus) {
  fill: currentColor;
  d: path("M15 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
