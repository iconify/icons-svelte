<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l6cp2-b8s"/><path class="k_2z93bzc"/><path class="jcknv4b7x"/><path class="igenzcbop"/><path class="u20-axb8k"/><path class="a7vpafiwa"/><path class="n3p0zmbop"/><path class="zwn7edcbm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:for-each-duotone-regular" {...props}></Icon>
<style>
:global(.a7vpafiwa) {
  d: path("M6 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.igenzcbop) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15.8 3.84a9 9 0 1 1 -7.6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jcknv4b7x) {
  fill: currentColor;
  d: path("M16 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.k_2z93bzc) {
  fill: currentColor;
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.l6cp2-b8s) {
  fill: currentColor;
  d: path("M6 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n3p0zmbop) {
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u20-axb8k) {
  d: path("M15.8 3.84a9 9 0 1 1 -7.6 0");
}

:global(.zwn7edcbm) {
  d: path("M16 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
