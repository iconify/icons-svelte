<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q4dbwx7ej"/><path class="kti78mmln"/><path class="xt4rfzb9z"/><path class="yix-58bnj"/><path class="moha5wbmp"/><path class="ov4z8dh4a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hallucination-detect-duotone-regular" {...props}></Icon>
<style>
:global(.kti78mmln) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M22 12a12.5 12.5 0 0 1 -20 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.moha5wbmp) {
  d: path("M22 12a12.5 12.5 0 0 1 -20 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ov4z8dh4a) {
  d: path("m8 13.5 2.5 -2.5 2.5 2.5 2.5 -2.5");
}

:global(.q4dbwx7ej) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 12a12.5 12.5 0 0 1 20 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xt4rfzb9z) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 13.5 2.5 -2.5 2.5 2.5 2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yix-58bnj) {
  d: path("M2 12a12.5 12.5 0 0 1 20 0");
}

</style>
