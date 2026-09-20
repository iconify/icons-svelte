<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="jho4t4trq"/><path class="maj2ufb3h"/><path class="nbz__qqtx"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="d4s5t4bpo"/><path class="y4-ssjnrw"/><path class="j4if4rbfv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chart-bar-duotone-bold" {...props}></Icon>
<style>
:global(.d4s5t4bpo) {
  d: path("M8 12v8");
}

:global(.dh-nlhghu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.j4if4rbfv) {
  d: path("M18 14v6");
}

:global(.jho4t4trq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 12v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jiw8u-asa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.maj2ufb3h) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nbz__qqtx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
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

:global(.y4-ssjnrw) {
  d: path("M13 8v12");
}

</style>
