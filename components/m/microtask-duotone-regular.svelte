<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x6e_qy8ax"/><path class="xvl0zubxy"/><path class="ze6_11znx"/><path class="fizmkteml"/><path class="g8vjt7b7p"/><path class="zey5ebc0a"/><path class="r7dhdp-mq"/><path class="umr6jbb1c"/><path class="j7phtvv5f"/><path class="ceatt7y_b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:microtask-duotone-regular" {...props}></Icon>
<style>
:global(.ceatt7y_b) {
  d: path("M18 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.fizmkteml) {
  fill: currentColor;
  d: path("M4 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.g8vjt7b7p) {
  fill: currentColor;
  d: path("M18 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.j7phtvv5f) {
  d: path("M4 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r7dhdp-mq) {
  d: path("M4 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.umr6jbb1c) {
  d: path("M18 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.x6e_qy8ax) {
  fill: currentColor;
  d: path("M7 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xvl0zubxy) {
  fill: currentColor;
  d: path("M4 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ze6_11znx) {
  fill: currentColor;
  d: path("M18 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zey5ebc0a) {
  d: path("M7 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

</style>
