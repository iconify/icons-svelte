<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="r_r678bum"/><path class="lqiw_3bos"/><path class="xyhj-ubbr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chart-gantt-outline-bold" {...props}></Icon>
<style>
:global(.lqiw_3bos) {
  d: path("M10 12h7");
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.r_r678bum) {
  d: path("M6 7h6");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xyhj-ubbr) {
  d: path("M13 17h7");
}

</style>
