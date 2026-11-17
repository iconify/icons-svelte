<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wo2rjobjt"/><path class="p7etf2lyb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bus-side-duotone" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.p7etf2lyb) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 18a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2M9 18h6M3 10h12M9 5v5m6-5v7h6M5 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

:global(.wo2rjobjt) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 5h14a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2a1.999 1.999 0 0 0-3-1.732c-.619.357-1 1.017-1 1.732H9a1.999 1.999 0 0 0-3-1.732c-.619.357-1 1.017-1 1.732a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2");
}

</style>
