<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x-titfblx"/><path class="h35q2qaeh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:microphone-stand" {...props}></Icon>
<style>
:global(.h35q2qaeh) {
  d: path("M6 9a6 6 0 0 0 12 0m-6 6v6.5m-4.5 0L12 18l4.5 3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x-titfblx) {
  d: path("M12 2.5za3 3 0 0 1 3 3v4a3 3 0 0 1-3 3a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3");
}

</style>
