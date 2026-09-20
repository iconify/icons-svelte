<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jkh2r59sx"/><path class="qrhqs_vfa"/><path class="ktrb23c8t"/><path class="ke5wwvpzo"/><path class="tp7101bon"/><path class="yb0d-pkkp"/><path class="qxpc-f42y"/><path class="f5e6x3ddq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:aisle-duotone-thin" {...props}></Icon>
<style>
:global(.f5e6x3ddq) {
  d: path("M14.5 12v7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jkh2r59sx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ke5wwvpzo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14.5 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ktrb23c8t) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qrhqs_vfa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 8v14h16V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qxpc-f42y) {
  d: path("M9.5 12v7");
}

:global(.tp7101bon) {
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
}

:global(.yb0d-pkkp) {
  d: path("M4 8v14h16V8");
}

</style>
