<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r-5e-memd"/><path class="hr63ej0sj"/><path class="xe-06hb6o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-vineyard" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hr63ej0sj) {
  d: path("M7 13.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m5 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

:global(.r-5e-memd) {
  d: path("M4.5 9.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m5 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m5 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

:global(.xe-06hb6o) {
  d: path("M9.5 18a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M12 7c0-2 1-3.25 3-3.5");
}

</style>
