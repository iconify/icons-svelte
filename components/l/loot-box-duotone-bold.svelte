<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zqacdi7pw"/><path class="g55pkgb9q"/><path class="gy24xikbq"/><path class="ynb6hvbvw"/><path class="d4yxbb03p"/><path class="sv8lhpyik"/><path class="d8abqfbpc"/><path class="ivnzz4jio"/><path class="i9jx3nbss"/><path class="buphzhbcx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:loot-box-duotone-bold" {...props}></Icon>
<style>
:global(.buphzhbcx) {
  d: path("m15 9 2 -2");
}

:global(.d4yxbb03p) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 9 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d8abqfbpc) {
  d: path("M3 11h18");
}

:global(.g55pkgb9q) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gy24xikbq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 8V5");
  opacity: var(--svg-opacity--0-2, 0.2);
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

:global(.ynb6hvbvw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 9 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zqacdi7pw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 11v9h14v-9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
