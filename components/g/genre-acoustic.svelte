<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xc4jwvwfh"/><path class="qrcu_7ngk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:genre-acoustic" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qrcu_7ngk) {
  d: path("M10.25 17a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

:global(.xc4jwvwfh) {
  d: path("M12 9.5c-2.75 0-4.5 1.25-4.5 3.25c0 1 .5 1.5.75 2c-1.75.75-2.75 2-2.75 3.5c0 2 2.5 3.25 6.5 3.25s6.5-1.25 6.5-3.25c0-1.5-1-2.75-2.75-3.5c.25-.5.75-1 .75-2c0-2-1.75-3.25-4.5-3.25m0-7za1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 12 6a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 12 2.5M12 6v3.5");
}

</style>
