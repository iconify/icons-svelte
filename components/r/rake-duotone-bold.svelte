<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k4nfprbzz"/><path class="dem7zwy2d"/><path class="m8ef0m9xo"/><path class="ov5pw4sxv"/><path class="p8zr033kc"/><path class="lkej6mbow"/><path class="qv6cnabrq"/><path class="oqj-o0b2r"/><path class="ktxjg3b2q"/><path class="evsu0jbbm"/><path class="drjad9bfe"/><path class="zpusjcvvn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rake-duotone-bold" {...props}></Icon>
<style>
:global(.dem7zwy2d) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 14h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.drjad9bfe) {
  d: path("M14 14v4");
}

:global(.evsu0jbbm) {
  d: path("M10 14v4");
}

:global(.k4nfprbzz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ktxjg3b2q) {
  d: path("M6 14v4");
}

:global(.lkej6mbow) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m8ef0m9xo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oqj-o0b2r) {
  d: path("M5 14h14");
}

:global(.ov5pw4sxv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p8zr033kc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qv6cnabrq) {
  d: path("M12 3v11");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.zpusjcvvn) {
  d: path("M18 14v4");
}

</style>
