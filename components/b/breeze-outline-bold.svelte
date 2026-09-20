<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="d7smd9b8i"/><path class="v5_ol6yqz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:breeze-outline-bold" {...props}></Icon>
<style>
:global(.d7smd9b8i) {
  d: path("M2 8h13a3.5 3.5 0 1 0 -3.5 -3.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v5_ol6yqz) {
  d: path("M2 17h12a3.5 3.5 0 1 0 -3.5 3.5");
}

</style>
