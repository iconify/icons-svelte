<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jusf72b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:rocking-chair-sharp" {...props}></Icon>
<style>
:global(.jusf72b4k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 3.25L7.5 13.5h9M6.95 8.75h6.55v4.75m-5.25 0l-1 6m8.5-6l1 6m-13-1.5c3 2.75 13.5 2.75 16.5 0");
}

</style>
