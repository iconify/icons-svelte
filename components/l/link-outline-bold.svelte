<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wn_zu_bwn"/><path class="qi0s8ibkf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:link-outline-bold" {...props}></Icon>
<style>
:global(.qi0s8ibkf) {
  d: path("M16.5 9H19a3 3 0 0 1 3 3 3 3 0 0 1 -3 3h-5a3 3 0 0 1 -3 -3 3 3 0 0 1 3 -3Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wn_zu_bwn) {
  d: path("M7.5 9H10a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3 3 3 0 0 1 3 -3Z");
}

</style>
