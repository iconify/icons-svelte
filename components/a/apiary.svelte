<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5wjvkbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:apiary" {...props}></Icon>
<style>
:global(.b5wjvkbxt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8.5L12 3l8.5 5.5Zm3.75 0h9.5a1.75 1.75 0 0 1 1.75 1.75v9.5a1.75 1.75 0 0 1-1.75 1.75h-9.5a1.75 1.75 0 0 1-1.75-1.75v-9.5A1.75 1.75 0 0 1 7.25 8.5M5.5 15h13M10 18.25h4");
}

</style>
