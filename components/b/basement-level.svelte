<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="heqp9ubet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:basement-level" {...props}></Icon>
<style>
:global(.heqp9ubet) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 21.5v-13L12 3l6 5.5v13ZM6 10h12M2.5 15.5h2m3 0h2m1.5 0h2m1.5 0h2m3 0h2");
}

</style>
