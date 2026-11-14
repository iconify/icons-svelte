<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zg2q79ben"/><path class="df978zbzh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mooring-ball" {...props}></Icon>
<style>
:global(.df978zbzh) {
  d: path("M10 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0M3 20q3-2.25 6 0t6 0t6 0M6.5 11.5h11");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zg2q79ben) {
  d: path("M6.5 11.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

</style>
