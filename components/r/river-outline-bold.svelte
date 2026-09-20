<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nq6698b_y"/><path class="he-6-nbhf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:river-outline-bold" {...props}></Icon>
<style>
:global(.he-6-nbhf) {
  d: path("M14 3v6l6 6v6");
}

:global(.nq6698b_y) {
  d: path("M4 3v6l6 6v6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
