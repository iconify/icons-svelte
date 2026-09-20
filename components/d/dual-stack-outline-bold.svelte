<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x43bekb2j"/><path class="n-g2uz0bh"/><path class="zwghjjvbs"/><path class="gt7coxqxq"/><path class="gvmht2kii"/><path class="ifhv18rgk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dual-stack-outline-bold" {...props}></Icon>
<style>
:global(.gt7coxqxq) {
  d: path("M3 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.gvmht2kii) {
  d: path("M3 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ifhv18rgk) {
  d: path("M12 12h6");
}

:global(.n-g2uz0bh) {
  d: path("M2 8h7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x43bekb2j) {
  d: path("M9 10a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-8a2 2 0 0 1 -2 -2Z");
}

:global(.zwghjjvbs) {
  d: path("M2 16h7");
}

</style>
