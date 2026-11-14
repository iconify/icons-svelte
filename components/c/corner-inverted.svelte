<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abcw2ablw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:corner-inverted" {...props}></Icon>
<style>
:global(.abcw2ablw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5h11a6 6 0 0 0 6 6v11h-17Z");
}

</style>
