<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcpwjnwuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cut" {...props}></Icon>
<style>
:global(.bcpwjnwuh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 17.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m11 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-5.75-2.25L17 4.5m-1.75 10.75L7 4.5");
}

</style>
