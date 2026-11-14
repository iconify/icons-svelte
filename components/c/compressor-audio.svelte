<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zm06ebbul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:compressor-audio" {...props}></Icon>
<style>
:global(.zm06ebbul) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 8.5h8v7H8Zm4-6v3.25m-2.5-2.5l2.5 2.5l2.5-2.5M12 21.5v-3.25m-2.5 2.5l2.5-2.5l2.5 2.5");
}

</style>
