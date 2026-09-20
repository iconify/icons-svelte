<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="u1uhlqgcz"/><path class="xzbn7sr9p"/><path class="akurgx2bb"/><path class="pvgr1jg2z"/><path class="em8xf33qp"/><path class="rw6ho_bav"/><path class="l2bljsbmn"/><path class="s7xlnnb_i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gift-box-duotone-bold" {...props}></Icon>
<style>
:global(.akurgx2bb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 9v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.em8xf33qp) {
  d: path("M4 9v11h16V9");
}

:global(.l2bljsbmn) {
  d: path("M12 9v11");
}

:global(.pvgr1jg2z) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 9 8 5h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rw6ho_bav) {
  d: path("M2 9h20");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s7xlnnb_i) {
  d: path("M12 9 8 5h4");
}

:global(.u1uhlqgcz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 9v11h16V9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xzbn7sr9p) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 9h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
