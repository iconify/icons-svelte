<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mtdcutbrr"/><path class="k2suf5bsg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:microphone-off-duotone" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.k2suf5bsg) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 8v3a3 3 0 0 0 3 3c.828 0 1.457-.457 2-1m1-5V6a3 3 0 0 0-3-3c-.572 0-.545-.278-1 0m1 15v3M5 10v1a7 7 0 0 0 7 7c1.933 0 3.733-.733 5-2M3 2l19 19");
}

:global(.mtdcutbrr) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 6v5a4 4 0 0 1-8 0V6a4 4 0 0 1 8 0");
}

</style>
