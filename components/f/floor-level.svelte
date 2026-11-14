<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgwg-10th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:floor-level" {...props}></Icon>
<style>
:global(.wgwg-10th) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 21.5v-13L15 3l6.5 5.5v13Zm0-13h13M8.5 15h13M12 11.75h.01m2.99 0h.01m2.99 0h.01M2.5 9l3 2.75l-3 2.75");
}

</style>
