<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6r6vojex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:courthouse" {...props}></Icon>
<style>
:global(.p6r6vojex) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.25 5.75l3.873-2.242a1.75 1.75 0 0 1 1.754 0L16.75 5.75a1.474 1.474 0 0 1-.739 2.75H7.989a1.474 1.474 0 0 1-.739-2.75M6 8.5v9m4-9v9m4-9v9m4-9v9m-14.5 0h17m-18 3h19");
}

</style>
