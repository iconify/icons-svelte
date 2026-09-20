<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fe9c5cduf"/><path class="ma7lidmyb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gold-label-outline-bold" {...props}></Icon>
<style>
:global(.fe9c5cduf) {
  d: path("M3 7h13l5 5 -5 5H3Z");
}

:global(.ma7lidmyb) {
  d: path("m6 12 2 2 3.5 -3.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
