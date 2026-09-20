<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xgzlj4bea"/><path class="l2bljsbmn"/><path class="u78lc2bnx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:lecture-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l2bljsbmn) {
  d: path("M12 9v11");
}

:global(.u78lc2bnx) {
  d: path("M6 20h12");
}

:global(.xgzlj4bea) {
  d: path("m5 8 3 -3h11v3Z");
}

</style>
