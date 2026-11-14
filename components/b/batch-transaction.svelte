<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e6olv-hqu"/><path class="qfi76c80d"/><path class="pi_3pdbah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:batch-transaction" {...props}></Icon>
<style>
:global(.e6olv-hqu) {
  d: path("M6 10h6a3.5 3.5 0 0 1 3.5 3.5v3A3.5 3.5 0 0 1 12 20H6a3.5 3.5 0 0 1-3.5-3.5v-3A3.5 3.5 0 0 1 6 10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pi_3pdbah) {
  d: path("M8.5 4h11a2 2 0 0 1 2 2v8M9 10v10");
}

:global(.qfi76c80d) {
  d: path("M5.5 7h11a2 2 0 0 1 2 2v8");
}

</style>
