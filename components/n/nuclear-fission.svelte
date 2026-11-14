<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6212dbzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:nuclear-fission" {...props}></Icon>
<style>
:global(.g6212dbzi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 6a6 6 0 0 0 0 12Zm6 0a6 6 0 0 1 0 12Zm-3 1h.01M12 10.5v3m0 3.5h.01");
}

</style>
