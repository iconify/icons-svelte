<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ybxmeccml"/><path class="z2ytn2b4x"/><path class="vspm3ybjo"/><path class="qcxa0jb0g"/><path class="ytov6dbof"/><path class="a3eibhdgt"/><path class="z26gfvqcs"/><path class="uct8v-rdb"/><path class="p47b7s_df"/><path class="j6_bngbnz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:car-cover-duotone-bold" {...props}></Icon>
<style>
:global(.a3eibhdgt) {
  d: path("M4.5 9.5a7.5 7.5 0 0 1 15 0");
}

:global(.j6_bngbnz) {
  d: path("M15 18.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.p47b7s_df) {
  d: path("M7 18.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.qcxa0jb0g) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4.5 9.5h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uct8v-rdb) {
  d: path("M4.5 18v-3L7 12.5h7.5L17 15h2.5v3");
}

:global(.vspm3ybjo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4.5 9.5a7.5 7.5 0 0 1 15 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ybxmeccml) {
  fill: currentColor;
  d: path("M7 18.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ytov6dbof) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4.5 18v-3L7 12.5h7.5L17 15h2.5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z26gfvqcs) {
  d: path("M4.5 9.5h15");
}

:global(.z2ytn2b4x) {
  fill: currentColor;
  d: path("M15 18.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
