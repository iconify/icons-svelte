<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5zenac3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:d-ring" {...props}></Icon>
<style>
:global(.r5zenac3b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3.5h2.5a8.5 8.5 0 0 1 0 17H10ZM10 9H2.5v6H10");
}

</style>
