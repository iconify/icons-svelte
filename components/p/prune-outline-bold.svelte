<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mpjdm200q"/><path class="ngnirel9c"/><path class="hcq4p1b2v"/><path class="b1a3u6bfq"/><path class="ax4bccbjb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:prune-outline-bold" {...props}></Icon>
<style>
:global(.ax4bccbjb) {
  d: path("m20 7 -4 4");
}

:global(.b1a3u6bfq) {
  d: path("m16 7 4 4");
}

:global(.hcq4p1b2v) {
  d: path("M6 15h8");
}

:global(.mpjdm200q) {
  d: path("M6 4v16");
}

:global(.ngnirel9c) {
  d: path("M6 9h8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
