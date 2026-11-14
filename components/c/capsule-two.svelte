<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pld2uylwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:capsule-two" {...props}></Icon>
<style>
:global(.pld2uylwg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 4.5a2.75 2.75 0 0 1 4 4l-6 6a2.75 2.75 0 0 1-4-4Zm7 5a2.75 2.75 0 0 1 4 4l-6 6a2.75 2.75 0 0 1-4-4Zm-10-2l4 4m3 1l4 4");
}

</style>
