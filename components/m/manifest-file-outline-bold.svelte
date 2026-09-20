<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tks4a4biu"/><path class="lgr612izs"/><path class="fhluz1bdh"/><path class="i6r7zygac"/><path class="wyp7k2b7p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:manifest-file-outline-bold" {...props}></Icon>
<style>
:global(.fhluz1bdh) {
  d: path("M11 12h5");
}

:global(.i6r7zygac) {
  d: path("M8 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.lgr612izs) {
  d: path("M8 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tks4a4biu) {
  d: path("M13 3H6v18h12V8Z");
}

:global(.wyp7k2b7p) {
  d: path("M11 16h5");
}

</style>
