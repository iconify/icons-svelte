<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ezg__mbcy"/><path class="fjs2tubqx"/><path class="t4hxo2bao"/><path class="cvkofmywl"/><path class="qu79-qujw"/><path class="xmopbdc-t"/><path class="d1zyr9bfc"/><path class="if5ft31dv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:alert-duotone-regular" {...props}></Icon>
<style>
:global(.cvkofmywl) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 4v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d1zyr9bfc) {
  d: path("M12 4v4");
}

:global(.ezg__mbcy) {
  fill: currentColor;
  d: path("M11 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fjs2tubqx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 15a7 7 0 0 1 14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.if5ft31dv) {
  d: path("M11 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qu79-qujw) {
  d: path("M5 15a7 7 0 0 1 14 0");
}

:global(.t4hxo2bao) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 15h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xmopbdc-t) {
  d: path("M5 15h14");
}

</style>
