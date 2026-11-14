<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="crmehveme"/><path class="s4ks0gbcq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:binder-clip" {...props}></Icon>
<style>
:global(.crmehveme) {
  d: path("M7.5 8h-1a2 2 0 0 0-2 2v9.5a2 2 0 0 0 2 2h11a2 2 0 0 0 2-2V10a2 2 0 0 0-2-2h-1");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s4ks0gbcq) {
  d: path("M9.25 6.5h5.5a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 14.75 12h-5.5a1.75 1.75 0 0 1-1.75-1.75v-2A1.75 1.75 0 0 1 9.25 6.5m-.75 0l-2-4h4v4m5 0l2-4h-4v4");
}

</style>
