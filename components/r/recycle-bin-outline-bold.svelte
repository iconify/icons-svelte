<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mvvbl7zxc"/><path class="vhnbtvbtn"/><path class="spg3og_ww"/><path class="f6kbfx-8d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:recycle-bin-outline-bold" {...props}></Icon>
<style>
:global(.f6kbfx-8d) {
  d: path("m9 17 3 -3 3 3");
}

:global(.mvvbl7zxc) {
  d: path("M6 8v13h12V8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.spg3og_ww) {
  d: path("M9 8V5h6v3");
}

:global(.vhnbtvbtn) {
  d: path("M3 8h18");
}

</style>
