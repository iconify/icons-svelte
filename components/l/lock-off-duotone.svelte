<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jit_-dybp"/><path class="kjutkzuud"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:lock-off-duotone" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.jit_-dybp) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 21H6a2.003 2.003 0 0 1-2-2v-7a2.003 2.003 0 0 1 2-2h1Zm-5-11h5a2.003 2.003 0 0 1 2 2v5Z");
}

:global(.kjutkzuud) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 21H6a2 2 0 0 1-2-2v-7a2 2 0 0 1 2-2h1m6 0h5a2 2 0 0 1 2 2v5M9 6a3 3 0 0 1 6 0v4M2 5l17 17");
}

</style>
