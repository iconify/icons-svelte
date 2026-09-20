<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k2jzr9u7f"/><path class="qnck32bfn"/><path class="qju4uubmq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:referee-outline-regular" {...props}></Icon>
<style>
:global(.k2jzr9u7f) {
  d: path("M5 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qju4uubmq) {
  d: path("M15 5h6v9h-6Z");
}

:global(.qnck32bfn) {
  d: path("M4 16a4 4 0 0 1 8 0");
}

</style>
