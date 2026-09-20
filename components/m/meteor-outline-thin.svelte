<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="am6m0sb5o"/><path class="nkayykbew"/><path class="jnvfxxwun"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:meteor-outline-thin" {...props}></Icon>
<style>
:global(.am6m0sb5o) {
  d: path("M16 4.5 19.5 8 16 11.5 12.5 8Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jnvfxxwun) {
  d: path("m7 21 5 -5");
}

:global(.nkayykbew) {
  d: path("m3 19 7 -7");
}

</style>
