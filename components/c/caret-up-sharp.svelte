<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o730c7bfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:caret-up-sharp" {...props}></Icon>
<style>
:global(.o730c7bfg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 15.75h14.542l-1.842-1.7l-6-5.6l-.7-.686l-.7.686l-6 5.6l-1.842 1.7z");
}

</style>
