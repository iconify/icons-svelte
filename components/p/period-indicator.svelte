<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r6da7polz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:period-indicator" {...props}></Icon>
<style>
:global(.r6da7polz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.563 3.137a9 9 0 0 1 7.3 7.3m0 3.126a9 9 0 0 1-7.3 7.3m-3.126 0a9 9 0 0 1-7.3-7.3m0-3.126a9 9 0 0 1 7.3-7.3M12 12h.01");
}

</style>
