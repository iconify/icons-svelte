<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aktctcc7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:currency-yen" {...props}></Icon>
<style>
:global(.aktctcc7w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 4.5l5.5 7l5.5-7m-5.5 7v8M8 13h8m-8 3.25h8");
}

</style>
