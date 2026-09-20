<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ozi-k-boi"/><path class="wlp3ibbib"/><path class="c3wl0l-ou"/><path class="yhbiuccel"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:funnel-drop-outline-thin" {...props}></Icon>
<style>
:global(.c3wl0l-ou) {
  d: path("M19 13v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ozi-k-boi) {
  d: path("M3 7h18");
}

:global(.wlp3ibbib) {
  d: path("M6 13h12");
}

:global(.yhbiuccel) {
  d: path("m16 16 3 3 3 -3");
}

</style>
