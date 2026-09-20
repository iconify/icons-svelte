<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h2-2dgnfu"/><path class="tdul-wdwn"/><path class="vy337188j"/><path class="rjrs_5bsc"/><path class="xslfg2evh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:height-measure-outline-bold" {...props}></Icon>
<style>
:global(.h2-2dgnfu) {
  d: path("M12 3v18");
}

:global(.rjrs_5bsc) {
  d: path("M6 3h12");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tdul-wdwn) {
  d: path("m9 6 3 -3 3 3");
}

:global(.vy337188j) {
  d: path("m9 18 3 3 3 -3");
}

:global(.xslfg2evh) {
  d: path("M6 21h12");
}

</style>
