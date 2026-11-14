<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vlf_y8wtt"/><path class="f86karbur"/><path class="tg_64rbjj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:health-risk-high" {...props}></Icon>
<style>
:global(.f86karbur) {
  fill: currentColor;
  d: path("M10 6.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tg_64rbjj) {
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m0 5.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.vlf_y8wtt) {
  d: path("M12 2.5za5 5 0 0 1 5 5v9a5 5 0 0 1-5 5a5 5 0 0 1-5-5v-9a5 5 0 0 1 5-5");
}

</style>
