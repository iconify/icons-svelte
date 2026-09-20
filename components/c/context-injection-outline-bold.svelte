<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pmd2fdz0m"/><path class="wj4cfmbhq"/><path class="lrtehacrs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:context-injection-outline-bold" {...props}></Icon>
<style>
:global(.lrtehacrs) {
  d: path("m6 9 3 3 -3 3");
}

:global(.pmd2fdz0m) {
  d: path("M9 5a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2h-8a2 2 0 0 1 -2 -2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wj4cfmbhq) {
  d: path("M2 12h7");
}

</style>
