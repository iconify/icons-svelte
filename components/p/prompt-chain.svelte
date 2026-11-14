<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="to2eysbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:prompt-chain" {...props}></Icon>
<style>
:global(.to2eysbhq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8.5H7v7H2.5Zm7.25 0h4.5v7h-4.5Zm7.25 0h4.5v7H17ZM7 12h2.75m4.5 0H17");
}

</style>
