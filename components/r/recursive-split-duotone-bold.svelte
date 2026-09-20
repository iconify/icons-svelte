<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h68oqyb7w"/><path class="qtnzvq5nm"/><path class="s89cttbmk"/><path class="zyplbtn7l"/><path class="o--b0kbyk"/><path class="km05dlbsw"/><path class="c7dgfu7wx"/><path class="lgyhdeb-s"/><path class="j1kezkxcy"/><path class="ezp0d4btt"/><path class="gnit4mb6c"/><path class="lkpe2ldcq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:recursive-split-duotone-bold" {...props}></Icon>
<style>
:global(.c7dgfu7wx) {
  d: path("M2 4h20");
}

:global(.ezp0d4btt) {
  d: path("M2 16h3");
}

:global(.gnit4mb6c) {
  d: path("M7.5 16h3");
}

:global(.h68oqyb7w) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 4h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.j1kezkxcy) {
  d: path("M13.5 10H22");
}

:global(.km05dlbsw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13.5 16H22");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lgyhdeb-s) {
  d: path("M2 10h8.5");
}

:global(.lkpe2ldcq) {
  d: path("M13.5 16H22");
}

:global(.o--b0kbyk) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7.5 16h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qtnzvq5nm) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 10h8.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s89cttbmk) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13.5 10H22");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zyplbtn7l) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 16h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
