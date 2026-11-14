<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nb6fasbvt"/><path class="l02t2qs1j"/><path class="vypfsppjx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:concurrency" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l02t2qs1j) {
  d: path("M19.5 3.5L21 6l-2.75 1M3 18q8-7 16-4");
}

:global(.nb6fasbvt) {
  d: path("M5 10q8-7 16-4");
}

:global(.vypfsppjx) {
  d: path("M17.5 11.5L19 14l-2.75 1");
}

</style>
