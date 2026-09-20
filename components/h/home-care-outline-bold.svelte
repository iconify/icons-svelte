<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hwufvfb8q"/><path class="i5wd616ky"/><path class="mvm7r4bea"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:home-care-outline-bold" {...props}></Icon>
<style>
:global(.hwufvfb8q) {
  d: path("M3 20v-8l9 -9 9 9v8Z");
}

:global(.i5wd616ky) {
  d: path("M12 10v8");
}

:global(.mvm7r4bea) {
  d: path("M8 14h8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
