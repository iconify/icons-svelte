<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="okud9xj_d"/><path class="rw6ho_bav"/><path class="nimfanbbl"/><path class="ew8lc9fxa"/><path class="fpad0ccyb"/><path class="yu4dpkbwa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fuse-box-outline-bold" {...props}></Icon>
<style>
:global(.ew8lc9fxa) {
  d: path("M10 11v6");
}

:global(.fpad0ccyb) {
  d: path("M14 11v6");
}

:global(.nimfanbbl) {
  d: path("M6 11v6");
}

:global(.okud9xj_d) {
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
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

:global(.yu4dpkbwa) {
  d: path("M18 11v6");
}

</style>
