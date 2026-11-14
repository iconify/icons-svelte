<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnbtvsieh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:badge-veteran" {...props}></Icon>
<style>
:global(.jnbtvsieh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 9l9-4.5L21 9M3 14.5l9-4.5l9 4.5M3 20l9-4.5l9 4.5");
}

</style>
