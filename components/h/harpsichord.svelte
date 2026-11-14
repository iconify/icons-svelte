<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc6f4z87h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:harpsichord" {...props}></Icon>
<style>
:global(.cc6f4z87h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.5H11c3.5 0 5.5-3.5 10.5-3.5v9h-19Zm2 5.5l.5 7.5M19.5 13l-.5 7.5M2.5 10.25H10");
}

</style>
