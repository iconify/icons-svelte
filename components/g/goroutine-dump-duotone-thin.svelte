<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m8c8atiya"/><path class="hhrpd0mfr"/><path class="w2535ybvu"/><path class="pt53j2b9d"/><path class="wkp4c939u"/><path class="imsvhcbjm"/><path class="n0n63pb2v"/><path class="g587irb4v"/><path class="hv3ppsbji"/><path class="hd5-m5bld"/><path class="ffipo4b5s"/><path class="h1j63eveo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:goroutine-dump-duotone-thin" {...props}></Icon>
<style>
:global(.ffipo4b5s) {
  d: path("M9 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.g587irb4v) {
  d: path("M7 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.h1j63eveo) {
  d: path("M13 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hd5-m5bld) {
  d: path("M15 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hhrpd0mfr) {
  fill: currentColor;
  d: path("M7 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hv3ppsbji) {
  d: path("M11 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.imsvhcbjm) {
  fill: currentColor;
  d: path("M13 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.m8c8atiya) {
  fill: currentColor;
  d: path("M4 15v4h16v-4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n0n63pb2v) {
  d: path("M4 15v4h16v-4");
}

:global(.pt53j2b9d) {
  fill: currentColor;
  d: path("M15 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.w2535ybvu) {
  fill: currentColor;
  d: path("M11 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wkp4c939u) {
  fill: currentColor;
  d: path("M9 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
