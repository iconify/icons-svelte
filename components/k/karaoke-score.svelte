<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kb3frcbft"/><path class="fa60uub9j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:karaoke-score" {...props}></Icon>
<style>
:global(.fa60uub9j) {
  d: path("M9.25 8.75L3 17.5l2 2l6.75-8.25M15 19.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m3.5 0v-5L21 16");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kb3frcbft) {
  d: path("M9 7a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

</style>
