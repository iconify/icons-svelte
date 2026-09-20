<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hn4kykb4m"/><path class="iz9s08bfh"/><path class="alkjmdb2u"/><path class="h4jktfbaf"/><path class="a3eibhdgt"/><path class="z26gfvqcs"/><path class="ts5ij9bsc"/><path class="zm2dyvb-o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:health-cover-duotone-thin" {...props}></Icon>
<style>
:global(.a3eibhdgt) {
  d: path("M4.5 9.5a7.5 7.5 0 0 1 15 0");
}

:global(.alkjmdb2u) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h4jktfbaf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 16h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hn4kykb4m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4.5 9.5a7.5 7.5 0 0 1 15 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iz9s08bfh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4.5 9.5h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ts5ij9bsc) {
  d: path("M12 13v6");
}

:global(.z26gfvqcs) {
  d: path("M4.5 9.5h15");
}

:global(.zm2dyvb-o) {
  d: path("M9 16h6");
}

</style>
