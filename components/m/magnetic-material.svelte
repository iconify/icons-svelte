<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ei5ee3bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:magnetic-material" {...props}></Icon>
<style>
:global(.ei5ee3bny) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3v9a7 7 0 0 0 14 0V3h-4v9a3 3 0 0 1-6 0V3Zm0 4h4m6 0h4");
}

</style>
