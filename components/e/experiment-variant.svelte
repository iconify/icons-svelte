<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duf06ohjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:experiment-variant" {...props}></Icon>
<style>
:global(.duf06ohjm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5v-6c0-3-5.5-3-5.5-6v-.75M12 15.5c0-3 5.5-3 5.5-6v-.75M3.5 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm11-3h6v6h-6Z");
}

</style>
