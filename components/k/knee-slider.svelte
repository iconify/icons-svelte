<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zd-jh8b-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:knee-slider" {...props}></Icon>
<style>
:global(.zd-jh8b-a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9c0-2.5 2-3.5 4-3.5h10c2 0 4 1 4 3.5v4c0 3.5-4 5.5-9 5.5s-9-2-9-5.5Zm5 0h.01M16 14.5h.01");
}

</style>
