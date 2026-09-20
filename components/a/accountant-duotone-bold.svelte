<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="le41ikb_c"/><path class="a69mrrrgx"/><path class="uou3ur5dw"/><path class="pemn838wn"/><path class="ia4sldbfw"/><path class="uftinba5h"/><path class="o3bdao7ob"/><path class="o62mcobgu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:accountant-duotone-bold" {...props}></Icon>
<style>
:global(.a69mrrrgx) {
  fill: currentColor;
  d: path("M8.5 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ia4sldbfw) {
  d: path("M3 21a9 9 0 0 1 18 0");
}

:global(.le41ikb_c) {
  fill: currentColor;
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.o3bdao7ob) {
  d: path("m9 20 6 -6");
}

:global(.o62mcobgu) {
  d: path("M13.5 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.pemn838wn) {
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uftinba5h) {
  d: path("M8.5 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.uou3ur5dw) {
  fill: currentColor;
  d: path("M13.5 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
