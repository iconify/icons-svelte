<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iile52bem"/><path class="jotk81b5q"/><path class="dvrab6bph"/><path class="xslfg2evh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:operating-room-outline-thin" {...props}></Icon>
<style>
:global(.dvrab6bph) {
  d: path("M3 15a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v2.5a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iile52bem) {
  d: path("M6 8a6 6 0 0 1 12 0");
}

:global(.jotk81b5q) {
  d: path("M12 2v6");
}

:global(.xslfg2evh) {
  d: path("M6 21h12");
}

</style>
