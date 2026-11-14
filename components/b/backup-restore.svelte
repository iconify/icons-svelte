<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wntovpb7d"/><path class="xd81l6sko"/><path class="whi-fg93u"/><path class="x4gomqbbj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:backup-restore" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.whi-fg93u) {
  d: path("M9.25 8.25v7.5a3.25 1.25 0 0 0 6.5 0v-7.5");
}

:global(.wntovpb7d) {
  d: path("M5.5 16a8 8 0 1 0-1-4");
}

:global(.x4gomqbbj) {
  d: path("M9.25 12.25a3.25 1.25 0 0 0 6.5 0");
}

:global(.xd81l6sko) {
  d: path("m2.5 10l2 2l2-2m2.75-1.75a3.25 1.25 0 1 0 6.5 0a3.25 1.25 0 1 0-6.5 0");
}

</style>
