<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thla3ebwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bacteria-x" {...props}></Icon>
<style>
:global(.thla3ebwp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 6.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm8.75 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-7.75 9a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm11 0l5 5m0-5l-5 5");
}

</style>
