<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jal3bn45q"/><path class="dj0lbhr2u"/><path class="dt7zp_wra"/><path class="x50q_4bdr"/><path class="s3pa5qb5b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:iceberg-table-duotone-bold" {...props}></Icon>
<style>
:global(.dj0lbhr2u) {
  fill: currentColor;
  d: path("M7 13h10l-5 5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.dt7zp_wra) {
  d: path("M12 4.5 14.5 7h-5Z");
}

:global(.jal3bn45q) {
  fill: currentColor;
  d: path("M12 4.5 14.5 7h-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s3pa5qb5b) {
  d: path("M7 13h10l-5 5Z");
}

:global(.x50q_4bdr) {
  d: path("M3 10h18");
}

</style>
