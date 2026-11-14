<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9xi554mk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:leaves-branch" {...props}></Icon>
<style>
:global(.n9xi554mk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21V8m-2-3a2 3 0 1 0 4 0a2 3 0 1 0-4 0Zm2 8.5Q10.25 9.25 5.5 9q1.75 4.25 6.5 4.5Zm0 3.75q1.75-4.25 6.5-4.5q-1.75 4.25-6.5 4.5ZM12 21q-1.75-4.25-6.5-4.5Q7.25 20.75 12 21Z");
}

</style>
