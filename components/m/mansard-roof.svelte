<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="govl2crwh"/><path class="qgerh9utl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mansard-roof" {...props}></Icon>
<style>
:global(.govl2crwh) {
  d: path("m4.315 11.172l2.275-6.5A1.75 1.75 0 0 1 8.242 3.5h7.516a1.75 1.75 0 0 1 1.652 1.172l2.275 6.5a1.75 1.75 0 0 1-1.652 2.328H5.967a1.75 1.75 0 0 1-1.652-2.328");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qgerh9utl) {
  d: path("M5.5 13.5V21h13v-7.5");
}

</style>
