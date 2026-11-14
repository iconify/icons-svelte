<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uh6kfjb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:proposal-sent" {...props}></Icon>
<style>
:global(.uh6kfjb5q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8h11v14H3Zm18.5-5.5l-7 3l3 1.5l1.5 3.5Zm-4 4.5l4-4.5M6 13h5m-5 4h3.5");
}

</style>
