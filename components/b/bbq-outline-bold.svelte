<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="u38qczjqj"/><path class="yl27xj7ez"/><path class="ev1ejqbjw"/><path class="ozu7q9bor"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bbq-outline-bold" {...props}></Icon>
<style>
:global(.ev1ejqbjw) {
  d: path("m8 18 -3 3");
}

:global(.ozu7q9bor) {
  d: path("m16 18 3 3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u38qczjqj) {
  d: path("M4 11a8 8 0 0 1 16 0");
}

:global(.yl27xj7ez) {
  d: path("M4 13h16c0 3 -3 5 -8 5s-8 -2 -8 -5");
}

</style>
