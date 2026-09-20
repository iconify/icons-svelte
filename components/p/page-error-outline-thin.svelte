<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nzpsuduik"/><path class="vhnbtvbtn"/><path class="qwuiuke1m"/><path class="v-yxhlj3j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:page-error-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nzpsuduik) {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.qwuiuke1m) {
  d: path("m9.5 11.5 5 5");
}

:global(.v-yxhlj3j) {
  d: path("m14.5 11.5 -5 5");
}

:global(.vhnbtvbtn) {
  d: path("M3 8h18");
}

</style>
