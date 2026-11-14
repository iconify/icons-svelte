<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pf4kbnbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bushing" {...props}></Icon>
<style>
:global(.pf4kbnbpg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 4.5h4A3.5 3.5 0 0 1 17.5 8v8a3.5 3.5 0 0 1-3.5 3.5h-4A3.5 3.5 0 0 1 6.5 16V8A3.5 3.5 0 0 1 10 4.5M6.5 10h-4v4h4m11-4h4v4h-4");
}

</style>
