<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mj0-vmbss"/><path class="i2xa3obeh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:leader-elect-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i2xa3obeh) {
  d: path("M14.32 9.5a5.5 5.5 0 1 1 -4.64 0");
}

:global(.mj0-vmbss) {
  d: path("m8 7.5 2 -2 2 2 2 -2 2 2");
}

</style>
