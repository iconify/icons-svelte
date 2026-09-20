<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nkz3mtbwk"/><path class="xgzlj4bea"/><path class="l2bljsbmn"/><path class="u78lc2bnx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:lecture-duotone-regular" {...props}></Icon>
<style>
:global(.l2bljsbmn) {
  d: path("M12 9v11");
}

:global(.nkz3mtbwk) {
  fill: currentColor;
  d: path("m5 8 3 -3h11v3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u78lc2bnx) {
  d: path("M6 20h12");
}

:global(.xgzlj4bea) {
  d: path("m5 8 3 -3h11v3Z");
}

</style>
