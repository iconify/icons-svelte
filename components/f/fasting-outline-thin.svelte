<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s6lrl6bmb"/><path class="xwfp38btc"/><path class="mfc7nxp-y"/><path class="ag9m5ebdy"/><path class="kp83gfxow"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fasting-outline-thin" {...props}></Icon>
<style>
:global(.ag9m5ebdy) {
  d: path("M12 7v13");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kp83gfxow) {
  d: path("M4 20 16 8");
}

:global(.mfc7nxp-y) {
  d: path("M9 7h6");
}

:global(.s6lrl6bmb) {
  d: path("M9 4v3");
}

:global(.xwfp38btc) {
  d: path("M15 4v3");
}

</style>
