<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n09nomjwg"/><path class="hpmnlabtt"/><path class="kvfieo68l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:header-injection-outline-bold" {...props}></Icon>
<style>
:global(.hpmnlabtt) {
  d: path("M6 9h12");
}

:global(.kvfieo68l) {
  d: path("M13.5 11 11 13.5h2.5L11 16");
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

</style>
