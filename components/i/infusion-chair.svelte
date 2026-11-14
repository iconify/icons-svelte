<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c8hmcy6ke"/><path class="vjasm2neh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:infusion-chair" {...props}></Icon>
<style>
:global(.c8hmcy6ke) {
  d: path("m3 6l3 8h7.5l3 4.5M5.75 10.75h4.75M7.5 14v5.5M12 14v5.5m-6.5 0H14m6 2v-18h-3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vjasm2neh) {
  d: path("M17 5.5za1.75 1.75 0 0 1 1.75 1.75v1.5A1.75 1.75 0 0 1 17 10.5a1.75 1.75 0 0 1-1.75-1.75v-1.5A1.75 1.75 0 0 1 17 5.5");
}

</style>
