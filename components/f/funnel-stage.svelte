<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyg7y2edn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:funnel-stage" {...props}></Icon>
<style>
:global(.xyg7y2edn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4h17L14 10.5v8l-4 2v-10Zm2.75 2.75h11.5M8.5 9h7");
}

</style>
