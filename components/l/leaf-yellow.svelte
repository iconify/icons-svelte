<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emldwzlrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:leaf-yellow" {...props}></Icon>
<style>
:global(.emldwzlrl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 20C3 9 10 3 21 3c0 11-6 18-17 17m-1 1l9-9m-2.5-2h.01m4.99 3.5h.01");
}

</style>
