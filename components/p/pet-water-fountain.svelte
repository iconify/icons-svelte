<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5kcyachg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pet-water-fountain" {...props}></Icon>
<style>
:global(.e5kcyachg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 15h18q-.5 5.5-9 5.5T3 15Zm7.5 0V7.5h3V15m-3-7.5q-4.5-1-5 4.5m8-4.5q4.5-1 5 4.5M12 3.75h.01");
}

</style>
