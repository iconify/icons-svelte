<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ftqzjnb8u"/><path class="bzecsub_a"/><path class="mi_m6achy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:egress-outline-thin" {...props}></Icon>
<style>
:global(.bzecsub_a) {
  d: path("M8 12h12");
}

:global(.ftqzjnb8u) {
  d: path("M6 3v18");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mi_m6achy) {
  d: path("m17 9 3 3 -3 3");
}

</style>
