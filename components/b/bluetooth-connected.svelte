<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzc90kbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bluetooth-connected" {...props}></Icon>
<style>
:global(.fzc90kbxu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 7.5l9.5 8.5l-4.5 4.5v-17L16.5 8L7 16.5M3.5 12h.01m16.99 0h.01");
}

</style>
