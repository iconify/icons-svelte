<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jasdwvbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:head-up-display" {...props}></Icon>
<style>
:global(.jasdwvbmb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 18l2-11q6.5-2 13 0l2 11q-8.5-1.5-17 0ZM8 13.5h8M9 11v2.5m3-3.75v3.75m3-2.5v2.5");
}

</style>
