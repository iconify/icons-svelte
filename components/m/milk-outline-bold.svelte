<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t2e2ofbwt"/><path class="f8gsx7b5s"/><path class="gcalxb98a"/><path class="qtxvlht3c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:milk-outline-bold" {...props}></Icon>
<style>
:global(.f8gsx7b5s) {
  d: path("M6 8h12");
}

:global(.gcalxb98a) {
  d: path("M8 13h8");
}

:global(.qtxvlht3c) {
  d: path("M8 17h8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t2e2ofbwt) {
  d: path("M6 21V8l4 -4h4l4 4v13Z");
}

</style>
