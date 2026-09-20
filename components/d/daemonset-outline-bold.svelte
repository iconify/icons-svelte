<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pmuiqo95v"/><path class="m_m6c4t8g"/><path class="f73i47bnv"/><path class="e6q34etyy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:daemonset-outline-bold" {...props}></Icon>
<style>
:global(.e6q34etyy) {
  d: path("M16 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.f73i47bnv) {
  d: path("M9 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.m_m6c4t8g) {
  d: path("M2 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.pmuiqo95v) {
  d: path("M2 17h20");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
