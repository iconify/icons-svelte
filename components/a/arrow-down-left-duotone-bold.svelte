<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="v922o3vez"/><path class="bo841zbxr"/><path class="piaam4vpr"/><path class="i67dqei2u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-down-left-duotone-bold" {...props}></Icon>
<style>
:global(.bo841zbxr) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 10v10h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i67dqei2u) {
  d: path("M4 10v10h10");
}

:global(.piaam4vpr) {
  d: path("M20 4 4 20");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v922o3vez) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 4 4 20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
