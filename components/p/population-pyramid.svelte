<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd1xo9wuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:population-pyramid" {...props}></Icon>
<style>
:global(.kd1xo9wuq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 20.5v-4h2v-4h2v-4h2v-4h5v4h2v4h2v4h2v4Zm8.5-18v19");
}

</style>
