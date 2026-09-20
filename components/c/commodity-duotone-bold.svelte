<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yhgteobra"/><path class="uepyaybdp"/><path class="v0b-4fwch"/><path class="uhf5s-b6r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:commodity-duotone-bold" {...props}></Icon>
<style>
:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uepyaybdp) {
  fill: currentColor;
  d: path("m5 11 4.5 -4.5h5L19 11Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.uhf5s-b6r) {
  d: path("m5 11 4.5 -4.5h5L19 11Z");
}

:global(.v0b-4fwch) {
  d: path("m2 19 5 -5h10l5 5Z");
}

:global(.yhgteobra) {
  fill: currentColor;
  d: path("m2 19 5 -5h10l5 5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
