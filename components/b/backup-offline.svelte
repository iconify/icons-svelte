<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qm2rh_7kn"/><path class="qs851bbzf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:backup-offline" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qm2rh_7kn) {
  d: path("M7.278 3.287c1.326-.336 2.96-.537 4.722-.537c4.4 0 8 1.25 8 2.75v10.555m-3.239 4.648c-1.332.342-2.981.547-4.761.547c-4.4 0-8-1.25-8-2.75V7.891");
}

:global(.qs851bbzf) {
  d: path("M12.147 8.25C16.48 8.222 20 6.983 20 5.5M4 12c0 1.359 2.955 2.513 6.783 2.718m7-.827C19.155 13.395 20 12.727 20 12M3.5 3.5l17 17");
}

</style>
