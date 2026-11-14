<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xfzjhfk0n"/><path class="cbv7gduxy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:crypto-portfolio" {...props}></Icon>
<style>
:global(.cbv7gduxy) {
  d: path("M13.75 13.75h7.75a7.75 7.75 0 0 1-7.75 7.75Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xfzjhfk0n) {
  d: path("M11 11h7.75A7.75 7.75 0 1 0 11 18.75Z");
}

</style>
