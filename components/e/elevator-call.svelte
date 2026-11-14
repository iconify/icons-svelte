<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u07prvbqz"/><path class="ja8_zg6om"/><path class="ln-k0e6ba"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:elevator-call" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ja8_zg6om) {
  d: path("M6.5 12a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

:global(.ln-k0e6ba) {
  d: path("M9.5 12L12 9.5l2.5 2.5M12 9.5V15");
}

:global(.u07prvbqz) {
  d: path("M8.75 2.5h6.5a5.25 5.25 0 0 1 5.25 5.25v8.5a5.25 5.25 0 0 1-5.25 5.25h-6.5a5.25 5.25 0 0 1-5.25-5.25v-8.5A5.25 5.25 0 0 1 8.75 2.5");
}

</style>
