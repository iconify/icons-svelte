<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ad-aj6bxz"/><path class="xbkq17beg"/><path class="bprf6vbci"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:policy-cooling-off" {...props}></Icon>
<style>
:global(.ad-aj6bxz) {
  d: path("M7 4.5h10A3.5 3.5 0 0 1 20.5 8v10a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 18V8A3.5 3.5 0 0 1 7 4.5M3.5 9h17M8 2.5V6m8-3.5V6");
}

:global(.bprf6vbci) {
  d: path("m10.5 11.75l-2 2l2 2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xbkq17beg) {
  d: path("M8.5 13.75H14a2.25 2.25 0 0 1 0 4.5h-3.5");
}

</style>
