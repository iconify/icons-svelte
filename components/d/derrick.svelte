<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aeakvrbns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:derrick" {...props}></Icon>
<style>
:global(.aeakvrbns) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2h5v3h-5Zm.5 3L4 22M14 5l6 17M8.25 10l10 7m-2.5-7l-10 7M2 22h20");
}

</style>
