<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="saf7cel-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:reception-desk-hospital" {...props}></Icon>
<style>
:global(.saf7cel-p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 12.5a5.5 5.5 0 0 1 11 0ZM12 7V5m-1.5 0h3m-11 10.5h19V21h-19Z");
}

</style>
