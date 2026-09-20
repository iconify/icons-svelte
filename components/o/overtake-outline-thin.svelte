<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hcn-wubvk"/><path class="toy0nxbdm"/><path class="ler50rfbf"/><path class="caiwqabfd"/><path class="qw9zcf0wd"/><path class="beunabbsv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:overtake-outline-thin" {...props}></Icon>
<style>
:global(.beunabbsv) {
  d: path("M12.5 6.5 15 4l2.5 2.5");
}

:global(.caiwqabfd) {
  d: path("M6.5 10.5 9 8l2.5 2.5");
}

:global(.hcn-wubvk) {
  d: path("M3 2v20");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ler50rfbf) {
  d: path("M9 8v12");
}

:global(.qw9zcf0wd) {
  d: path("M15 4v12");
}

:global(.toy0nxbdm) {
  d: path("M21 2v20");
}

</style>
