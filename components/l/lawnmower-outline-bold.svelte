<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q737qqeus"/><path class="hkrm8eiuq"/><path class="aq5i5tblx"/><path class="l4egjkszt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:lawnmower-outline-bold" {...props}></Icon>
<style>
:global(.aq5i5tblx) {
  d: path("M4 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hkrm8eiuq) {
  d: path("m16 13 5 -5");
}

:global(.l4egjkszt) {
  d: path("M12 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.q737qqeus) {
  d: path("M4 11v4h12v-4Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
