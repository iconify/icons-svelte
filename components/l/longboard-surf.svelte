<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wqhz4w1aa"/><path class="aiucu5zzp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:longboard-surf" {...props}></Icon>
<style>
:global(.aiucu5zzp) {
  d: path("M7.75 18L11 20.5l-1.25-3.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wqhz4w1aa) {
  d: path("M4 19c0-5.5 9.5-15 15-15c0 5.5-9.5 15-15 15");
}

</style>
