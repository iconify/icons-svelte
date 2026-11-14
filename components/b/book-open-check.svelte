<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g35ndtbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:book-open-check" {...props}></Icon>
<style>
:global(.g35ndtbrv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21 12.967V4.5q-6-.75-9 1.5q-3-2.25-9-1.5v14q6-.75 9 1.5a7 7 0 0 1 .48-.329M12 6v11.9m0 .2V20m2.75-2l2 2L21 15.75");
}

</style>
