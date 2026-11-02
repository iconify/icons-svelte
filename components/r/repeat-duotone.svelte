<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c0_zos1-s"/><path class="iamlb7blu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:repeat-duotone" {...props}></Icon>
<style>
:global(.c0_zos1-s) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 8a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.iamlb7blu) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 11V8a2 2 0 0 1 2-2h16m-3 3l3-3l-3-3m3 10v3a2 2 0 0 1-2 2H3m3-3l-3 3l3 3");
}

</style>
