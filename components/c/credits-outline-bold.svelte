<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lh7nxd5dq"/><path class="ji-xh3b0v"/><path class="byqxsebzj"/><path class="p8a31xr4o"/><path class="lveb61hbp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:credits-outline-bold" {...props}></Icon>
<style>
:global(.byqxsebzj) {
  d: path("M16 8h6");
}

:global(.ji-xh3b0v) {
  d: path("M8 10.5v3");
}

:global(.lh7nxd5dq) {
  d: path("M3 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

:global(.lveb61hbp) {
  d: path("M16 16h6");
}

:global(.p8a31xr4o) {
  d: path("M16 12h6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
