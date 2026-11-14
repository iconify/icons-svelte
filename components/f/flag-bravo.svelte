<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nge4pkb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:flag-bravo" {...props}></Icon>
<style>
:global(.nge4pkb5u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3v18M5 4h14l-3.5 4.5L19 13H5");
}

</style>
