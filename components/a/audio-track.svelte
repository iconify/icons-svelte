<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bse5ou7xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:audio-track" {...props}></Icon>
<style>
:global(.bse5ou7xb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 8.25v3m4-6v9M12 2.5V17m4-11.25v8m4-5.5v3M3 20.5h18");
}

</style>
