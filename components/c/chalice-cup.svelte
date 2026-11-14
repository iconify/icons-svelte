<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="df1hg2pmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chalice-cup" {...props}></Icon>
<style>
:global(.df1hg2pmo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3h14v4A7 6 0 0 1 5 7Zm7 10v8.5m-4.5 0h9");
}

</style>
