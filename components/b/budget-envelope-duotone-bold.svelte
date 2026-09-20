<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="e10hmz-ui"/><path class="uxahocbdu"/><path class="nreq_9ofo"/><path class="csyuhrrop"/><path class="gr1zxddav"/><path class="hgjyjobhk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:budget-envelope-duotone-bold" {...props}></Icon>
<style>
:global(.csyuhrrop) {
  d: path("M5 14V3h14v11");
}

:global(.e10hmz-ui) {
  fill: currentColor;
  d: path("M2 11v10h20V11L12 21Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.gr1zxddav) {
  d: path("M9 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.hgjyjobhk) {
  d: path("M12 7v4");
}

:global(.nreq_9ofo) {
  d: path("M2 11v10h20V11L12 21Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uxahocbdu) {
  fill: currentColor;
  d: path("M9 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
