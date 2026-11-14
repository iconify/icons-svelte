<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tux3sqb_r"/><path class="incr9o5-e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:recipient-id-check" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.incr9o5-e) {
  d: path("M5.75 11a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M13 9.5h5M13 13h3");
}

:global(.tux3sqb_r) {
  d: path("M6.5 5.5h11A3.5 3.5 0 0 1 21 9v6a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 15V9a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
