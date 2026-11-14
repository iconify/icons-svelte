<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxfhwg7mw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:frame-stack-vertical" {...props}></Icon>
<style>
:global(.bxfhwg7mw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3H12v7.5H3.5Zm0 10.5H12V21H3.5Zm15-10v17M15.75 18l2.75 2.75L21.25 18");
}

</style>
