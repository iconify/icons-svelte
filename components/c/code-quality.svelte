<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxbkz2bda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:code-quality" {...props}></Icon>
<style>
:global(.vxbkz2bda) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.8 19H3V2.5h13v12.8M6.5 7h6m-6 4h4m4.25 7l2 2L21 15.75");
}

</style>
