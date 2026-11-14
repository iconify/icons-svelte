<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vlf_y8wtt"/><path class="uc5b-_4yv"/><path class="r15rq3brz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:health-risk-low" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r15rq3brz) {
  fill: currentColor;
  d: path("M10 17.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.uc5b-_4yv) {
  d: path("M10 6.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.vlf_y8wtt) {
  d: path("M12 2.5za5 5 0 0 1 5 5v9a5 5 0 0 1-5 5a5 5 0 0 1-5-5v-9a5 5 0 0 1 5-5");
}

</style>
