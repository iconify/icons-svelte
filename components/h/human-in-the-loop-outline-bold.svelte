<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="l8unaacgj"/><path class="ufzn_r3vk"/><path class="b_e_avbfy"/><path class="e69i7fcek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:human-in-the-loop-outline-bold" {...props}></Icon>
<style>
:global(.b_e_avbfy) {
  d: path("M7 19a5 5 0 0 1 10 0");
}

:global(.e69i7fcek) {
  d: path("M17 12h5");
}

:global(.l8unaacgj) {
  d: path("M2 12h5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ufzn_r3vk) {
  d: path("M9 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
