<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jfmvsgbrx"/><path class="wdjmdsb7h"/><path class="nm7sxz4gr"/><path class="y1x43_b7q"/><path class="wr45-4gqz"/><path class="ojq3d2bwe"/><path class="v28q9db1j"/><path class="hbuw0obat"/><path class="r7pmyrb1c"/><path class="vcbx2ik3k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:jailbreak-duotone-thin" {...props}></Icon>
<style>
:global(.hbuw0obat) {
  d: path("M17 3v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jfmvsgbrx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nm7sxz4gr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 3v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ojq3d2bwe) {
  d: path("M5 3v18");
}

:global(.r7pmyrb1c) {
  d: path("M14 15h5");
}

:global(.v28q9db1j) {
  d: path("M11 3v18");
}

:global(.vcbx2ik3k) {
  d: path("m17 12 3 3 -3 3");
}

:global(.wdjmdsb7h) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wr45-4gqz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m17 12 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y1x43_b7q) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 15h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
