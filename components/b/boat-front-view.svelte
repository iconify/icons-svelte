<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zj73v5x5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:boat-front-view" {...props}></Icon>
<style>
:global(.zj73v5x5p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 13h17c0 5-3.5 8-8.5 8s-8.5-3-8.5-8Zm2 0L12 2.5L18.5 13M12 2.5V13");
}

</style>
