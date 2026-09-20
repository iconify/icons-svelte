<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nguhiybnr"/><path class="r411km12t"/><path class="ez1_3xbuo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:drill-outline-bold" {...props}></Icon>
<style>
:global(.ez1_3xbuo) {
  d: path("M14 8h7");
}

:global(.nguhiybnr) {
  d: path("M4 5h10v6H4Z");
}

:global(.r411km12t) {
  d: path("M6 11v9h4v-9");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
