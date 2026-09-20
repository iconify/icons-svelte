<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="a-xmscbvb"/><path class="x7kl1kqgv"/><path class="ky48x0b1z"/><path class="lqo5h3m-x"/><path class="wjhuthx3n"/><path class="rpyanp93e"/><path class="nlx-15cix"/><path class="eylqpv51p"/><path class="a6m5kfb7k"/><path class="e7q8l6x6g"/><path class="osdsz4bam"/><path class="iup9trbmr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:git-bisect-duotone-bold" {...props}></Icon>
<style>
:global(.a-xmscbvb) {
  fill: currentColor;
  d: path("M4 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.a6m5kfb7k) {
  d: path("M18 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.e7q8l6x6g) {
  d: path("M6 14h5");
}

:global(.eylqpv51p) {
  d: path("M11 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.iup9trbmr) {
  d: path("M12 6v4");
}

:global(.ky48x0b1z) {
  fill: currentColor;
  d: path("M18 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.lqo5h3m-x) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 14h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nlx-15cix) {
  d: path("M4 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.osdsz4bam) {
  d: path("M13 14h5");
}

:global(.rpyanp93e) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 6v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wjhuthx3n) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 14h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x7kl1kqgv) {
  fill: currentColor;
  d: path("M11 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
