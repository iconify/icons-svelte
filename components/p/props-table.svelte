<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx1if7ojk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:props-table" {...props}></Icon>
<style>
:global(.xx1if7ojk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14h19M5 14l-1 7m15-7l1 7m-2.5-11H8a2 2 0 0 0 0 4h9.5Zm-9-7H16v7H8.5Zm3.75 0v3");
}

</style>
