<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gpip01bqy"/><path class="bod4n0b3z"/><path class="e-n_8dpfy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:landfill-outline-bold" {...props}></Icon>
<style>
:global(.bod4n0b3z) {
  d: path("M2 18h20");
}

:global(.e-n_8dpfy) {
  d: path("m9 13 2 -2");
}

:global(.gpip01bqy) {
  d: path("m3 15 5 -5 5 5 5 -5 3 3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
