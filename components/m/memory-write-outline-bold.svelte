<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n09nomjwg"/><path class="y5k8b5bfa"/><path class="hokxmxb-u"/><path class="v0p8rqbku"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:memory-write-outline-bold" {...props}></Icon>
<style>
:global(.hokxmxb-u) {
  d: path("M13 9v6");
}

:global(.n09nomjwg) {
  d: path("M15 6h3a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V9a3 3 0 0 1 3 -3h3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v0p8rqbku) {
  d: path("m18 10 -2 2 2 2");
}

:global(.y5k8b5bfa) {
  d: path("M9 9v6");
}

</style>
