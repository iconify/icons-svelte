<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qgak1bhch"/><path class="lao25xf0o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:origin-point" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lao25xf0o) {
  fill: currentColor;
  d: path("M10 9.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.qgak1bhch) {
  d: path("M12 21.5s6.5-6 6.5-12a6.5 6.5 0 0 0-13 0c0 6 6.5 12 6.5 12");
}

</style>
