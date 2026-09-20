<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nlx-15cix"/><path class="eylqpv51p"/><path class="a6m5kfb7k"/><path class="e7q8l6x6g"/><path class="osdsz4bam"/><path class="iup9trbmr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:git-bisect-outline-thin" {...props}></Icon>
<style>
:global(.a6m5kfb7k) {
  d: path("M18 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.e7q8l6x6g) {
  d: path("M6 14h5");
}

:global(.eylqpv51p) {
  d: path("M11 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iup9trbmr) {
  d: path("M12 6v4");
}

:global(.nlx-15cix) {
  d: path("M4 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.osdsz4bam) {
  d: path("M13 14h5");
}

</style>
