<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yyjrwztqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:indicator-lamp" {...props}></Icon>
<style>
:global(.yyjrwztqt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 13.5h14v7H5Zm2.5 0V10a4.5 4.5 0 0 1 9 0v3.5m-13-9l2 2m15-2l-2 2");
}

</style>
