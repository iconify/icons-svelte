<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jpj6svb4n"/><circle class="u2vhcz6gc"/><path class="brk278bus"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:crosswalk" {...props}></Icon>
<style>
:global(.brk278bus) {
  d: path("m12.45 6.6l-1.2 3.45l1.8 1.65v2.4m-1.8-4.05l-1.5 4.05m-.6-5.4l1.05-1.8l2.1-.3l1.35 1.8l1.65.6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jpj6svb4n) {
  d: path("M4.5 16.75v4.5m3.75-4.5v4.5m3.75-4.5v4.5m3.75-4.5v4.5m3.75-4.5v4.5");
}

:global(.u2vhcz6gc) {
  cx: 12.9px;
  cy: 4.05px;
  r: 1.25px;
}

</style>
