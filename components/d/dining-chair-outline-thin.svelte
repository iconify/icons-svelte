<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ckxsheb0b"/><path class="z22xlf92i"/><path class="u3jess8hd"/><path class="o682nlgep"/><path class="r182r524c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dining-chair-outline-thin" {...props}></Icon>
<style>
:global(.ckxsheb0b) {
  d: path("M7 3v10h10V3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o682nlgep) {
  d: path("M17 16v5");
}

:global(.r182r524c) {
  d: path("M7 9h10");
}

:global(.u3jess8hd) {
  d: path("M7 16v5");
}

:global(.z22xlf92i) {
  d: path("M5 16h14");
}

</style>
