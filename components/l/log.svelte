<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="srh5kwbik"/><path class="ipqfo6m2n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:log" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ipqfo6m2n) {
  d: path("M6 7a3.25 5 0 0 1 0 10A3.25 5 0 0 1 6 7m0 3.5a.9 1.5 0 0 0 0 3a.9 1.5 0 0 0 0-3m5.5-.25h5m-3 3.5h5");
}

:global(.srh5kwbik) {
  d: path("M6 7h13a2.25 2.25 0 0 1 2.25 2.25v5.5A2.25 2.25 0 0 1 19 17H6A3.25 5 0 0 1 6 7");
}

</style>
