<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b085z62oi"/><path class="jn06adc8n"/><path class="rwpsfdbow"/><path class="ug-0q4bvr"/><path class="r3uz_wvor"/><path class="vvv_0v-7b"/><path class="auc4o2swl"/><path class="bu35rpbki"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hammock-duotone-regular" {...props}></Icon>
<style>
:global(.auc4o2swl) {
  d: path("M4 8c0 8 16 8 16 0");
}

:global(.b085z62oi) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 6v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bu35rpbki) {
  d: path("M4 12c0 7 16 7 16 0");
}

:global(.jn06adc8n) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 6v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r3uz_wvor) {
  d: path("M4 6v15");
}

:global(.rwpsfdbow) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 8c0 8 16 8 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ug-0q4bvr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 12c0 7 16 7 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vvv_0v-7b) {
  d: path("M20 6v15");
}

</style>
