<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="woq4i_0zf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ripe-fruit" {...props}></Icon>
<style>
:global(.woq4i_0zf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 6c-2-1-6.5-.5-6.5 4.5c0 4 2.5 7.5 5 7.5c.75 0 1-.5 1.5-.5s.75.5 1.5.5c.25 0 .5-.1.75-.25v-3.5a2 2 0 0 1 2-2h2.15c.1-.55.1-1.25.1-1.75C16.5 5.5 12 5 10 6Zm0 0l1-3.5M14.75 18l2 2L21 15.75");
}

</style>
