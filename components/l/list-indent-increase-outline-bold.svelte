<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xgrfb-bqu"/><path class="tee3b-ble"/><path class="xyj-l9cjp"/><path class="e4mg5wbxb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:list-indent-increase-outline-bold" {...props}></Icon>
<style>
:global(.e4mg5wbxb) {
  d: path("M3 9.5 5.5 12 3 14.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tee3b-ble) {
  d: path("M10 12h11");
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

</style>
