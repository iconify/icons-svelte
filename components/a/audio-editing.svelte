<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drhtq7b6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:audio-editing" {...props}></Icon>
<style>
:global(.drhtq7b6y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3h12a3.5 3.5 0 0 1 3.5 3.5v6A3.5 3.5 0 0 1 18 16H6a3.5 3.5 0 0 1-3.5-3.5v-6A3.5 3.5 0 0 1 6 3m6 13v4.5m-3.5 0h7m-9-13v4M9.25 6v7M12 8.5v2m2.75-3.75v5.5m2.75-4v2.5");
}

</style>
