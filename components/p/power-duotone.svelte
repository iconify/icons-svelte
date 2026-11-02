<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qfay3iu_t"/><path class="p4xbnib0u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:power-duotone" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.p4xbnib0u) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 7a7.81 7.81 0 0 1 1 11c-3.123 3.747-8.877 3.747-12 0A7.81 7.81 0 0 1 7 7m5-4v8");
}

:global(.qfay3iu_t) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4.19 13a7.81 7.81 0 1 1 15.622 0A7.81 7.81 0 1 1 4.19 13");
}

</style>
