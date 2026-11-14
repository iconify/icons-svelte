<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dgg4o7bhu"/><path class="u64s_qb1i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:course-dashboard" {...props}></Icon>
<style>
:global(.dgg4o7bhu) {
  d: path("M2.5 3.5h19v17h-19Zm0 5h19");
}

:global(.u64s_qb1i) {
  d: path("M6 12h4.5v5H6Zm8 3v2m3-4.5V17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
