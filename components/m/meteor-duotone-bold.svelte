<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aoul07b2h"/><path class="am6m0sb5o"/><path class="nkayykbew"/><path class="jnvfxxwun"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:meteor-duotone-bold" {...props}></Icon>
<style>
:global(.am6m0sb5o) {
  d: path("M16 4.5 19.5 8 16 11.5 12.5 8Z");
}

:global(.aoul07b2h) {
  fill: currentColor;
  d: path("M16 4.5 19.5 8 16 11.5 12.5 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.jnvfxxwun) {
  d: path("m7 21 5 -5");
}

:global(.nkayykbew) {
  d: path("m3 19 7 -7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
