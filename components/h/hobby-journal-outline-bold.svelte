<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="diipsobkl"/><path class="wuvisubmw"/><path class="zsd3khm8o"/><path class="ws9v8zbhe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hobby-journal-outline-bold" {...props}></Icon>
<style>
:global(.diipsobkl) {
  d: path("M5 3v18h14V3Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ws9v8zbhe) {
  d: path("M11 16h6");
}

:global(.wuvisubmw) {
  d: path("M8 3v18");
}

:global(.zsd3khm8o) {
  d: path("M16 3v9l-2 -2 -2 2V3");
}

</style>
