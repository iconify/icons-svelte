<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="u4ynq5rza"/><path class="y9bnwbc9b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:kabaddi" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.u4ynq5rza) {
  cx: 8px;
  cy: 5px;
  r: 2.25px;
}

:global(.y9bnwbc9b) {
  d: path("m9 9l-1.5 5L4 17.25v4M7.5 14l4.5 2.5l.75 4.75m-4-11.75L16.5 8m-8 2L4 12.5m16.25-9.75v3.5m0 2.75v3.5m0 2.75v3.5");
}

</style>
