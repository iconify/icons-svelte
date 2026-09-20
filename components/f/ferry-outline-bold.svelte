<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r0ugme01d"/><path class="tz2pshf0g"/><path class="vrecxx6kh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ferry-outline-bold" {...props}></Icon>
<style>
:global(.r0ugme01d) {
  d: path("M2 15h20l-5 5H7Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tz2pshf0g) {
  d: path("M7 15V9h10v6");
}

:global(.vrecxx6kh) {
  d: path("M9 6h6");
}

</style>
