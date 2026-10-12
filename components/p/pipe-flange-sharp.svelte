<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wj5rb-xhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pipe-flange-sharp" {...props}></Icon>
<style>
:global(.wj5rb-xhn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 5.25H15A4.75 4.75 0 0 1 19.75 10v8h-5v-7.75h-9Zm-3-1.5h3v8h-3zM13.5 18H21v3h-7.5z");
}

</style>
