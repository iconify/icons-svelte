<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="reyvph0yg"/><path class="ki-5h0s5c"/><path class="dgtjfobks"/><path class="ab_fsy82a"/><path class="p04-68bfh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:license-scan-outline-thin" {...props}></Icon>
<style>
:global(.ab_fsy82a) {
  d: path("M8.5 18a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.dgtjfobks) {
  d: path("M6 9.5h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ki-5h0s5c) {
  d: path("M6 6h12");
}

:global(.p04-68bfh) {
  d: path("m13.5 20 2 2");
}

:global(.reyvph0yg) {
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
