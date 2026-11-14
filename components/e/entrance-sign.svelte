<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mmqsyeb9y"/><path class="hs0n8kbwk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:entrance-sign" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hs0n8kbwk) {
  d: path("m14 5.75l2.75 2.75L14 11.25");
}

:global(.mmqsyeb9y) {
  d: path("M6.5 3h11A3.5 3.5 0 0 1 21 6.5v4a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 10.5v-4A3.5 3.5 0 0 1 6.5 3M12 14v7.5m-5.5-13h10.25");
}

</style>
