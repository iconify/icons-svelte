<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zey5ebc0a"/><path class="r7dhdp-mq"/><path class="umr6jbb1c"/><path class="j7phtvv5f"/><path class="ceatt7y_b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:microtask-outline-bold" {...props}></Icon>
<style>
:global(.ceatt7y_b) {
  d: path("M18 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.j7phtvv5f) {
  d: path("M4 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.r7dhdp-mq) {
  d: path("M4 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.umr6jbb1c) {
  d: path("M18 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.zey5ebc0a) {
  d: path("M7 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

</style>
