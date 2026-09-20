<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="diipsobkl"/><path class="s1m4z10fj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cat-flap-outline-bold" {...props}></Icon>
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

:global(.s1m4z10fj) {
  d: path("M8 21v-4c0 -2 8 -2 8 0v4");
}

</style>
