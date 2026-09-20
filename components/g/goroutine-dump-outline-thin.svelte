<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n0n63pb2v"/><path class="g587irb4v"/><path class="hv3ppsbji"/><path class="hd5-m5bld"/><path class="ffipo4b5s"/><path class="h1j63eveo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:goroutine-dump-outline-thin" {...props}></Icon>
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

:global(.n0n63pb2v) {
  d: path("M4 15v4h16v-4");
}

</style>
