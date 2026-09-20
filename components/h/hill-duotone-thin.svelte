<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jm0dssk2j"/><path class="aw_qbkbel"/><path class="ke8s6xb3g"/><path class="evcx__bzi"/><path class="t4l7c7bim"/><path class="xctejrqwn"/><path class="nqnw98byf"/><path class="olqfcgidt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hill-duotone-thin" {...props}></Icon>
<style>
:global(.aw_qbkbel) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 14a5 5 0 0 1 10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.evcx__bzi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 19h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jm0dssk2j) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 14a7 7 0 0 1 14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ke8s6xb3g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 14h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nqnw98byf) {
  d: path("M2 14h20");
}

:global(.olqfcgidt) {
  d: path("M6 19h12");
}

:global(.t4l7c7bim) {
  d: path("M2 14a7 7 0 0 1 14 0");
}

:global(.xctejrqwn) {
  d: path("M12 14a5 5 0 0 1 10 0");
}

</style>
