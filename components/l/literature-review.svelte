<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mq96khafr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:literature-review" {...props}></Icon>
<style>
:global(.mq96khafr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 14.5h18v7H3ZM5 8h14v6.5H5Zm8 0V3l1.75 1.5L16.5 3v5M7 14.5v7M9.75 8v6.5");
}

</style>
