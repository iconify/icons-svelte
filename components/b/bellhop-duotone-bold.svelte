<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w_x4iohoz"/><path class="gg7gi8bfs"/><path class="b9bmegbpx"/><path class="uw5kuce7r"/><path class="lps9qspxb"/><path class="zdricccut"/><path class="hc853a05m"/><path class="c6hn90blm"/><path class="b_5ug6ank"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bellhop-duotone-bold" {...props}></Icon>
<style>
:global(.b_5ug6ank) {
  d: path("M17 20.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.b9bmegbpx) {
  fill: currentColor;
  d: path("M17 20.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.c6hn90blm) {
  d: path("M8 20.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.gg7gi8bfs) {
  fill: currentColor;
  d: path("M8 20.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hc853a05m) {
  d: path("M7 13.5h13");
}

:global(.lps9qspxb) {
  d: path("M3 3h6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uw5kuce7r) {
  d: path("M3 3v18");
}

:global(.w_x4iohoz) {
  fill: currentColor;
  d: path("M7 18V9h13v9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zdricccut) {
  d: path("M7 18V9h13v9Z");
}

</style>
