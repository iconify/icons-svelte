<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpu49jkem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:clan-shield" {...props}></Icon>
<style>
:global(.cpu49jkem) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 9h15v4c0 4-3.5 6.75-7.5 8.5C8 19.75 4.5 17 4.5 13ZM8 9l-.5-5.5L10 6l2-3l2 3l2.5-2.5L16 9");
}

</style>
