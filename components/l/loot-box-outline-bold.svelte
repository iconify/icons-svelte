<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="sv8lhpyik"/><path class="d8abqfbpc"/><path class="ivnzz4jio"/><path class="i9jx3nbss"/><path class="buphzhbcx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:loot-box-outline-bold" {...props}></Icon>
<style>
:global(.buphzhbcx) {
  d: path("m15 9 2 -2");
}

:global(.d8abqfbpc) {
  d: path("M3 11h18");
}

:global(.i9jx3nbss) {
  d: path("M9 9 7 7");
}

:global(.ivnzz4jio) {
  d: path("M12 8V5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sv8lhpyik) {
  d: path("M5 11v9h14v-9");
}

</style>
