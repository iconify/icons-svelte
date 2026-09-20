<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dt7zp_wra"/><path class="x50q_4bdr"/><path class="s3pa5qb5b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:iceberg-table-outline-regular" {...props}></Icon>
<style>
:global(.dt7zp_wra) {
  d: path("M12 4.5 14.5 7h-5Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s3pa5qb5b) {
  d: path("M7 13h10l-5 5Z");
}

:global(.x50q_4bdr) {
  d: path("M3 10h18");
}

</style>
