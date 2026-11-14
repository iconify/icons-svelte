<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tzghz9bcj"/><path class="trihjcxls"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:address-book-pin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.trihjcxls) {
  d: path("M12.5 17s-3.75-3-3.75-6a3.75 3.75 0 0 1 7.5 0c0 3-3.75 6-3.75 6");
}

:global(.tzghz9bcj) {
  d: path("M9 2.5h7A3.5 3.5 0 0 1 19.5 6v12a3.5 3.5 0 0 1-3.5 3.5H9A3.5 3.5 0 0 1 5.5 18V6A3.5 3.5 0 0 1 9 2.5m-5.5 5h2m-2 4.5h2m-2 4.5h2");
}

</style>
