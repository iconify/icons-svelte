<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yt-s_ymok"/><path class="tfbr82yah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:business-livestock-cover" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tfbr82yah) {
  d: path("M9 17.5a3 1.75 0 1 0 6 0a3 1.75 0 1 0-6 0");
}

:global(.yt-s_ymok) {
  d: path("M12 9za5 5 0 0 1 5 5v1.5a5 5 0 0 1-5 5a5 5 0 0 1-5-5V14a5 5 0 0 1 5-5m-4.5 1.5c-2.5 0-4-2-4-4.5m13 4.5c2.5 0 4-2 4-4.5M10 13.5h.01m3.99 0h.01");
}

</style>
