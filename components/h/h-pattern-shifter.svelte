<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogp89-btt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:h-pattern-shifter" {...props}></Icon>
<style>
:global(.ogp89-btt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m3 3V17m-6.5-4v8m13-8v8m-13-4h13");
}

</style>
