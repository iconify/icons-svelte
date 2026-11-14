<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ya86gqukk"/><path class="rlcx1jh5a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:probability" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rlcx1jh5a) {
  d: path("M10 12a2 5.25 0 1 0 4 0a2 5.25 0 1 0-4 0m7.592-7.987a9.75 9.75 0 0 1 3.826 5.464m-15.01 10.51a9.75 9.75 0 0 1-3.826-5.464");
}

:global(.ya86gqukk) {
  d: path("M7.5 12a4.5 8.5 0 1 0 9 0a4.5 8.5 0 1 0-9 0");
}

</style>
