<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cuqhzt_vr"/><path class="qu01ihbhh"/><path class="ot0-u9bsz"/><path class="q01xb8b0t"/><path class="bwuo0ywji"/><path class="s9xdwbcyw"/><path class="pesxdybze"/><path class="nkayykbew"/><path class="b603-acaz"/><path class="adiugjbhs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:aggregate-duotone-thin" {...props}></Icon>
<style>
:global(.adiugjbhs) {
  d: path("m15 9 3 3 -3 3");
}

:global(.b603-acaz) {
  d: path("M10 12h8");
}

:global(.bwuo0ywji) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cuqhzt_vr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 5 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nkayykbew) {
  d: path("m3 19 7 -7");
}

:global(.ot0-u9bsz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 19 7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pesxdybze) {
  d: path("M3 12h7");
}

:global(.q01xb8b0t) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qu01ihbhh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s9xdwbcyw) {
  d: path("m3 5 7 7");
}

</style>
