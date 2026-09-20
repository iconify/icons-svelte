<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ohvm-m-da"/><path class="k_2z93bzc"/><path class="jcg2xu7sp"/><path class="n3p0zmbop"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dpad-duotone-regular" {...props}></Icon>
<style>
:global(.jcg2xu7sp) {
  d: path("M9 3h6v6h6v6h-6v6H9v-6H3V9h6Z");
}

:global(.k_2z93bzc) {
  fill: currentColor;
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

:global(.ohvm-m-da) {
  fill: currentColor;
  d: path("M9 3h6v6h6v6h-6v6H9v-6H3V9h6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
