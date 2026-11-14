<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2-998h1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ac-current" {...props}></Icon>
<style>
:global(.f2-998h1e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12c2-7 5.5-7 7.5 0s5.5 7 7.5 0m0 0h4");
}

</style>
