<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k187sabpz"/><path class="g9fextbgn"/><path class="f228956be"/><path class="k2jzr9u7f"/><path class="zcnxk5bij"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dining-table-outline-bold" {...props}></Icon>
<style>
:global(.f228956be) {
  d: path("M19 11v10");
}

:global(.g9fextbgn) {
  d: path("M5 11v10");
}

:global(.k187sabpz) {
  d: path("M2 11h20");
}

:global(.k2jzr9u7f) {
  d: path("M5 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.zcnxk5bij) {
  d: path("M13 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
