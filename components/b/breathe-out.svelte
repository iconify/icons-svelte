<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8_6wybeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:breathe-out" {...props}></Icon>
<style>
:global(.j8_6wybeb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM12 7V2.5m-1.75 1.75L12 2.5l1.75 1.75M12 17v4.5m-1.75-1.75L12 21.5l1.75-1.75M7 12H2.5m1.75-1.75L2.5 12l1.75 1.75M17 12h4.5m-1.75-1.75L21.5 12l-1.75 1.75");
}

</style>
