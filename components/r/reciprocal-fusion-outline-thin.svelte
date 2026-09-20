<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mjze8rg7o"/><path class="l1jjkky7x"/><path class="ts8wzccza"/><path class="mes08rb3g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reciprocal-fusion-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l1jjkky7x) {
  d: path("M8 18h8");
}

:global(.mes08rb3g) {
  d: path("M13.5 15.5 16 18l-2.5 2.5");
}

:global(.mjze8rg7o) {
  d: path("M9 2.5H3l7 7V12h4V9.5l7 -7h-6");
}

:global(.ts8wzccza) {
  d: path("M10.5 15.5 8 18l2.5 2.5");
}

</style>
