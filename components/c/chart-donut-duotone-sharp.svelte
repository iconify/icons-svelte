<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e0tv1qbgw"/><path class="ls7iozbbd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-donut-duotone-sharp" {...props}></Icon>
<style>
:global(.e0tv1qbgw) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 12a9 9 0 0 1 9-9a9 9 0 0 1 9 9a9 9 0 0 1-9 9a9 9 0 0 1-9-9m5.315 1.557a4.001 4.001 0 0 0 7.37-3.114a4.001 4.001 0 0 0-7.37 3.114");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.ls7iozbbd) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 0 0-18 0m5 0a4 4 0 1 0 8 0a4 4 0 0 0-8 0m4-9v5m4 4h5");
}

</style>
