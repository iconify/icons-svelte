<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpxx-uiqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bluetooth" {...props}></Icon>
<style>
:global(.kpxx-uiqk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 7.5l9.5 8.5l-4.5 4.5v-17L16.5 8L7 16.5");
}

</style>
