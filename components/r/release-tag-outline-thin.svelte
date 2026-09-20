<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x9kn15bcl"/><path class="a7vpafiwa"/><path class="msaz94ywr"/><path class="fmjpvzbts"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:release-tag-outline-thin" {...props}></Icon>
<style>
:global(.a7vpafiwa) {
  d: path("M6 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.fmjpvzbts) {
  d: path("M11 14h5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.msaz94ywr) {
  d: path("M11 10h7");
}

:global(.x9kn15bcl) {
  d: path("m2 12 7 -7h12v14H9Z");
}

</style>
