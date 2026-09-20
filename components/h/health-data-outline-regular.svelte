<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yix-58bnj"/><path class="moha5wbmp"/><path class="vzl8cib_u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:health-data-outline-regular" {...props}></Icon>
<style>
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

:global(.vzl8cib_u) {
  d: path("M9 12a1.5 1.5 0 0 1 3 0 1.5 1.5 0 0 1 3 0l-3 3Z");
}

:global(.yix-58bnj) {
  d: path("M2 12a12.5 12.5 0 0 1 20 0");
}

</style>
