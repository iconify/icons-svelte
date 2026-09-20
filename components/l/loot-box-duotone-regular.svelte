<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t2kt2djuj"/><path class="digwvcbca"/><path class="qrtseogvw"/><path class="sg_0cmqdh"/><path class="zy-blebfy"/><path class="sv8lhpyik"/><path class="d8abqfbpc"/><path class="ivnzz4jio"/><path class="i9jx3nbss"/><path class="buphzhbcx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:loot-box-duotone-regular" {...props}></Icon>
<style>
:global(.buphzhbcx) {
  d: path("m15 9 2 -2");
}

:global(.d8abqfbpc) {
  d: path("M3 11h18");
}

:global(.digwvcbca) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 11h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i9jx3nbss) {
  d: path("M9 9 7 7");
}

:global(.ivnzz4jio) {
  d: path("M12 8V5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qrtseogvw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 8V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sg_0cmqdh) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 9 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sv8lhpyik) {
  d: path("M5 11v9h14v-9");
}

:global(.t2kt2djuj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 11v9h14v-9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zy-blebfy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 9 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
