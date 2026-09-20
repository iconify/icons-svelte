<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lwit8ko_j"/><path class="mwvgb4bmz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:check-duotone-bold" {...props}></Icon>
<style>
:global(.lwit8ko_j) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m4 12 5.5 5.5L20 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mwvgb4bmz) {
  d: path("m4 12 5.5 5.5L20 7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
