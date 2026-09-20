<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="v79iaqbup"/><path class="t9i3hdb-v"/><path class="t0ah32bee"/><path class="gj4kfi4dw"/><path class="fy0ap9ban"/><path class="ae-e09b3w"/><path class="d26wznbgp"/><path class="wm3q5wbwg"/><path class="vblyu6b4h"/><path class="r3snlms8q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:air-freight-duotone-bold" {...props}></Icon>
<style>
:global(.ae-e09b3w) {
  d: path("M3 12h18");
}

:global(.d26wznbgp) {
  d: path("M13 12 7 6");
}

:global(.fy0ap9ban) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 12 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gj4kfi4dw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 12 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r3snlms8q) {
  d: path("m5 12 -2 2");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t0ah32bee) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m13 12 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t9i3hdb-v) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 12 7 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v79iaqbup) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vblyu6b4h) {
  d: path("m5 12 -2 -2");
}

:global(.wm3q5wbwg) {
  d: path("m13 12 -6 6");
}

</style>
