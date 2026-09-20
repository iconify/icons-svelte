<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="id4vqxf8c"/><path class="qlw91sbif"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:overfit-gap-outline-bold" {...props}></Icon>
<style>
:global(.id4vqxf8c) {
  d: path("m4 14 5 -5h11");
}

:global(.qlw91sbif) {
  d: path("m4 19 5 -5h4l4 4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
