<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="oe3oa5b3b"/><path class="yt7qsrz-s"/><path class="w08657bnd"/><path class="icy6dnbvy"/><path class="n-7t0yb1r"/><path class="esz0ytbwn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:balance-training-duotone-bold" {...props}></Icon>
<style>
:global(.esz0ytbwn) {
  d: path("M8 17a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.icy6dnbvy) {
  d: path("M12 8v5");
}

:global(.n-7t0yb1r) {
  d: path("M3 13h18");
}

:global(.oe3oa5b3b) {
  fill: currentColor;
  d: path("M9 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w08657bnd) {
  d: path("M9 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.yt7qsrz-s) {
  fill: currentColor;
  d: path("M8 17a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
