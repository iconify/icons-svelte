<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kl0_d31ng"/><path class="jiiejx8cb"/><path class="r43pq459m"/><path class="ckt-nxbxw"/><path class="vgy66lb4b"/><path class="h2-2dgnfu"/><path class="tdul-wdwn"/><path class="vy337188j"/><path class="rjrs_5bsc"/><path class="xslfg2evh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:height-measure-duotone-bold" {...props}></Icon>
<style>
:global(.ckt-nxbxw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 3h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h2-2dgnfu) {
  d: path("M12 3v18");
}

:global(.jiiejx8cb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 6 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kl0_d31ng) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r43pq459m) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 18 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
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

:global(.vgy66lb4b) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 21h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vy337188j) {
  d: path("m9 18 3 3 3 -3");
}

:global(.xslfg2evh) {
  d: path("M6 21h12");
}

</style>
