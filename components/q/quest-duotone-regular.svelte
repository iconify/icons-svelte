<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j3k8n70yi"/><path class="wx7ogdbqc"/><path class="xug64tbnj"/><path class="pt-3kkb2k"/><path class="ae0h5kb0o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:quest-duotone-regular" {...props}></Icon>
<style>
:global(.ae0h5kb0o) {
  d: path("M9 15h6");
}

:global(.j3k8n70yi) {
  fill: currentColor;
  d: path("M6 4v16h12V4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pt-3kkb2k) {
  d: path("M9 11h6");
}

:global(.wx7ogdbqc) {
  d: path("M6 4v16h12V4Z");
}

:global(.xug64tbnj) {
  d: path("M6 4C4 4 4 8 6 8");
}

</style>
