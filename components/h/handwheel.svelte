<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="czu33icqx"/><path class="ds8eh_bwb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:handwheel" {...props}></Icon>
<style>
:global(.czu33icqx) {
  d: path("M4.5 10a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0");
}

:global(.ds8eh_bwb) {
  d: path("M10 10a2 2 0 1 0 4 0a2 2 0 1 0-4 0m.25-1L5.5 6.25M13.75 9l4.75-2.75M12 12v9.5m-3.5 0h7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
