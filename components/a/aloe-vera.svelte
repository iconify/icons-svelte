<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spl6v7j8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:aloe-vera" {...props}></Icon>
<style>
:global(.spl6v7j8o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 20.5c-1.5-5.5-1-12 0-17c1 5 1.5 11.5 0 17Zm-1 0c-3-2-5.5-7-7-12c3 2.5 6 6.5 7 12Zm2 0c3-2 5.5-7 7-12c-3 2.5-6 6.5-7 12Z");
}

</style>
