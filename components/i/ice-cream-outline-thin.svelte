<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o-4bk_b4n"/><path class="tsceiyk7b"/><path class="hclo6jb2r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ice-cream-outline-thin" {...props}></Icon>
<style>
:global(.hclo6jb2r) {
  d: path("M8 16h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o-4bk_b4n) {
  d: path("M7 8a5 5 0 1 0 10 0A5 5 0 1 0 7 8");
}

:global(.tsceiyk7b) {
  d: path("m5 13 7 7 7 -7Z");
}

</style>
