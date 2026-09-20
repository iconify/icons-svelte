<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="murw5tb-p"/><path class="gb3i0xbuh"/><path class="d0oey7bgo"/><path class="k1llj9blt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:auto-increment-outline-bold" {...props}></Icon>
<style>
:global(.d0oey7bgo) {
  d: path("m14 11 3 -3 3 3");
}

:global(.gb3i0xbuh) {
  d: path("M5 12h7");
}

:global(.k1llj9blt) {
  d: path("M17 8v8");
}

:global(.murw5tb-p) {
  d: path("M2 9a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
