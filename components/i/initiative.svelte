<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rhfkm_b7x"/><path class="b8_1ksbkk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:initiative" {...props}></Icon>
<style>
:global(.b8_1ksbkk) {
  d: path("m10.25 8.75l-4.75.5l-1.75 3.25l4.75-1m6.75 2.25l-.5 4.75l-3.25 1.75l1-4.75m1-6.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-5 6.5l-4 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rhfkm_b7x) {
  d: path("M20.5 3.5c-5.5 0-10.5 3-12 8l4 4c5-1.5 8-6.5 8-12");
}

</style>
