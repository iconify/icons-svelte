<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-77m8b5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:optics" {...props}></Icon>
<style>
:global(.b-77m8b5d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3a14 14 0 0 1 0 18A14 14 0 0 1 9 3M2.5 8.5h3.75m-3.75 7h3.75m5.5-7l9.25 7m-9.25 0l9.25-7");
}

</style>
