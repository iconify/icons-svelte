<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnw0sg0it"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:opera-house-sharp" {...props}></Icon>
<style>
:global(.vnw0sg0it) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 19.5Q4.5 8 12 4.5q-1 7.5-2.25 15Zm9.75 0Q14 10 21.25 8q-1.5 5-1.75 11.5Zm-10 0h18.5");
}

</style>
