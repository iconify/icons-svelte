<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ugdbidcqi"/><path class="y6lkwobxm"/><path class="v3qgglbcl"/><path class="fzdzbsazn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:event-sourcing-agent-outline-bold" {...props}></Icon>
<style>
:global(.fzdzbsazn) {
  d: path("M16 9.5v5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ugdbidcqi) {
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
}

:global(.v3qgglbcl) {
  d: path("M12 9.5v5");
}

:global(.y6lkwobxm) {
  d: path("M8 9.5v5");
}

</style>
