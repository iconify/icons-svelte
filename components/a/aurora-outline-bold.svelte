<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="i67oc1bla"/><path class="nzhcuvf_z"/><path class="mkk0o-9le"/><path class="z9ittvbis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:aurora-outline-bold" {...props}></Icon>
<style>
:global(.i67oc1bla) {
  d: path("M5 16V8l4 -4");
}

:global(.mkk0o-9le) {
  d: path("M15 16V8l4 -4");
}

:global(.nzhcuvf_z) {
  d: path("M10 16V8l4 -4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
