<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ricsl-blc"/><path class="wneoubc6n"/><path class="fzby91bau"/><path class="ka7-gu1bd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:broadcast-outline-bold" {...props}></Icon>
<style>
:global(.fzby91bau) {
  d: path("M8.24 8.63a4 4 0 0 1 7.5 0");
}

:global(.ka7-gu1bd) {
  d: path("M5.42 7.61a7 7 0 0 1 13.16 0");
}

:global(.ricsl-blc) {
  d: path("M12 12v9");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wneoubc6n) {
  d: path("M7 21h10");
}

</style>
