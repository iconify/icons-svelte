<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wx7ogdbqc"/><path class="xug64tbnj"/><path class="pt-3kkb2k"/><path class="ae0h5kb0o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:quest-outline-bold" {...props}></Icon>
<style>
:global(.ae0h5kb0o) {
  d: path("M9 15h6");
}

:global(.pt-3kkb2k) {
  d: path("M9 11h6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wx7ogdbqc) {
  d: path("M6 4v16h12V4Z");
}

:global(.xug64tbnj) {
  d: path("M6 4C4 4 4 8 6 8");
}

</style>
