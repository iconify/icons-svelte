<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lzbpucbiv"/><path class="eg2u_0b1d"/><path class="r6xbnkbzi"/><path class="vw-f69bhv"/><path class="zoewprblb"/><path class="ojq3d2bwe"/><path class="v28q9db1j"/><path class="hbuw0obat"/><path class="r7pmyrb1c"/><path class="vcbx2ik3k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:jailbreak-duotone-bold" {...props}></Icon>
<style>
:global(.eg2u_0b1d) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hbuw0obat) {
  d: path("M17 3v6");
}

:global(.lzbpucbiv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ojq3d2bwe) {
  d: path("M5 3v18");
}

:global(.r6xbnkbzi) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 3v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r7pmyrb1c) {
  d: path("M14 15h5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v28q9db1j) {
  d: path("M11 3v18");
}

:global(.vcbx2ik3k) {
  d: path("m17 12 3 3 -3 3");
}

:global(.vw-f69bhv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 15h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zoewprblb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17 12 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
