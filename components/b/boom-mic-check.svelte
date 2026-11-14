<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k27n50qrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:boom-mic-check" {...props}></Icon>
<style>
:global(.k27n50qrt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17.25L10.75 9M13 4a2 2 0 0 1 3 0a2 2 0 0 1 3 0a3 3 0 0 1 0 6a2 2 0 0 1-3 0a2 2 0 0 1-3 0a3 3 0 0 1 0-6m1.75 14l2 2L21 15.75");
}

</style>
