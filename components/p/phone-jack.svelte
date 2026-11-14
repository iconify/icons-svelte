<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e69s43boz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:phone-jack" {...props}></Icon>
<style>
:global(.e69s43boz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 4.5h11a2 2 0 0 1 2 2v10h-4v3h-7v-3h-4v-10a2 2 0 0 1 2-2ZM9 8v3.5M12 8v3.5M15 8v3.5");
}

</style>
