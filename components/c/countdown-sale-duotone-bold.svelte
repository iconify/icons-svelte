<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ckt-nxbxw"/><path class="vgy66lb4b"/><path class="zz4ny369p"/><path class="qro1z5b9o"/><path class="rjrs_5bsc"/><path class="xslfg2evh"/><path class="b266jkbmh"/><path class="m-436sbse"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:countdown-sale-duotone-bold" {...props}></Icon>
<style>
:global(.b266jkbmh) {
  d: path("M7 3v4l5 5 5 -5V3");
}

:global(.ckt-nxbxw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 3h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m-436sbse) {
  d: path("M7 21v-4l5 -5 5 5v4");
}

:global(.qro1z5b9o) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 21v-4l5 -5 5 5v4");
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

:global(.vgy66lb4b) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 21h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xslfg2evh) {
  d: path("M6 21h12");
}

:global(.zz4ny369p) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 3v4l5 5 5 -5V3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
