<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="scqlh1bqt"/><path class="n-i8s48ix"/><path class="d6l2802on"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gif-search" {...props}></Icon>
<style>
:global(.d6l2802on) {
  d: path("m7.25 2l2 2l-2 2m8 11.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4 1.75L21 21");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n-i8s48ix) {
  d: path("m11.25 13.5l-2 2l2 2m-4.875-2.77A5.75 5.75 0 0 1 9.25 4");
}

:global(.scqlh1bqt) {
  d: path("M12.125 4.77A5.75 5.75 0 0 1 9.25 15.5");
}

</style>
