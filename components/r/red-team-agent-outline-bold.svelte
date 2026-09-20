<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="skbifdbcx"/><path class="mj0gsdv6h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:red-team-agent-outline-bold" {...props}></Icon>
<style>
:global(.mj0gsdv6h) {
  d: path("m18 10 -4.5 4.5H16L11.5 19");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.skbifdbcx) {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

</style>
