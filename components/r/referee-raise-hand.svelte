<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="juogkwkip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:referee-raise-hand" {...props}></Icon>
<style>
:global(.juogkwkip) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 4.5v7a4.5 4.5 0 0 0 9 0v-6m-6-3V9m3-6v6m-6 1.5l-3-3m5 7.75v6.25m5-6.25v6.25");
}

</style>
