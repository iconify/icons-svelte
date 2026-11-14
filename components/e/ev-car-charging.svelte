<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lba0ukgzr"/><path class="hry-z3bym"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ev-car-charging" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hry-z3bym) {
  d: path("M4.5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m8 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7 2.75l-3.75 3.5h4.5l-3.75 3.5");
}

:global(.lba0ukgzr) {
  d: path("M4.5 12h-2V9A1.5 1.5 0 0 1 4 7.5h1l2.5-4h6l2.5 4h2A1.5 1.5 0 0 1 19.5 9v3h-3m-8 0h4");
}

</style>
