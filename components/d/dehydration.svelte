<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iumsfqbzl"/><path class="kohs9ac4a"/><path class="aaayr3b6s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dehydration" {...props}></Icon>
<style>
:global(.aaayr3b6s) {
  d: path("M12.5 6.75L10.75 10l2.5 2l-1.75 3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iumsfqbzl) {
  d: path("M12 2.25C15.75 7 19.25 10.5 19.25 14.5s-3.25 7-7.25 7s-7.25-3-7.25-7S8.25 7 12 2.25");
}

:global(.kohs9ac4a) {
  fill: currentColor;
  d: path("M6.25 18.25h11.5c-1 2-3.25 3.25-5.75 3.25s-4.75-1.25-5.75-3.25");
}

</style>
