<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b_afn1bxu"/><path class="dm_wopyrf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:reserved-instance" {...props}></Icon>
<style>
:global(.b_afn1bxu) {
  d: path("M12.2 20.5H3v-16h16v7.8M3 9.5h16m-11-7v4m6-4v4M6.5 14H10m5 3.5h6v4h-6Z");
}

:global(.dm_wopyrf) {
  d: path("M16.5 17.5v-1a1.5 1.5 0 0 1 3 0v1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
