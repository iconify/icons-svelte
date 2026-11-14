<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psdmb8xlt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ad-mobile" {...props}></Icon>
<style>
:global(.psdmb8xlt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.1 20.5H3.5v-18h12v10.6M8 5.5h3m10.75 16.25h-4.5L14 18.5l4.5-4.5l3.25 3.25Zm-2.5-2.5h.01");
}

</style>
