<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z7gc_fb5f"/><path class="aiqsv8bpz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fish-cage" {...props}></Icon>
<style>
:global(.aiqsv8bpz) {
  d: path("M3.5 11.5q2.25-1.25 4.5 0t4.5 0t4.5 0t4.5 0M12 8v12m-5-4h10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z7gc_fb5f) {
  d: path("M2.5 4.5h19V8h-19ZM5 8l3 12h8l3-12");
}

</style>
