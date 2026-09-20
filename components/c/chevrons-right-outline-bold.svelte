<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="te2cn0btr"/><path class="pnu4jvbcb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chevrons-right-outline-bold" {...props}></Icon>
<style>
:global(.pnu4jvbcb) {
  d: path("m13 4 8 8 -8 8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.te2cn0btr) {
  d: path("m4 4 8 8 -8 8");
}

</style>
