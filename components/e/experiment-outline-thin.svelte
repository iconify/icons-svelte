<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fky40s_2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:experiment-outline-thin" {...props}></Icon>
<style>
:global(.fky40s_2v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3v7l-5 5v4h16v-4l-5 -5V3");
}

</style>
