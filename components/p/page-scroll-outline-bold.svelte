<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nzpsuduik"/><path class="vhnbtvbtn"/><path class="r5bn6xbek"/><path class="mqi2_ac9e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:page-scroll-outline-bold" {...props}></Icon>
<style>
:global(.mqi2_ac9e) {
  d: path("M9.5 15.5 12 18l2.5 -2.5");
}

:global(.nzpsuduik) {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.r5bn6xbek) {
  d: path("m9.5 11 2.5 2.5 2.5 -2.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vhnbtvbtn) {
  d: path("M3 8h18");
}

</style>
