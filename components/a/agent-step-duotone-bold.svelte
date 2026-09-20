<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g_1_9obcn"/><path class="jjd32ibec"/><path class="dxqp15kpa"/><path class="klyrig6if"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-step-duotone-bold" {...props}></Icon>
<style>
:global(.dxqp15kpa) {
  d: path("M8.69 8.37a4 4 0 1 1 -3.38 0");
}

:global(.g_1_9obcn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8.69 8.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jjd32ibec) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14 7 5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.klyrig6if) {
  d: path("m14 7 5 5 -5 5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
