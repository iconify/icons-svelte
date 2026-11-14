<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgywm__6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:folding-chair" {...props}></Icon>
<style>
:global(.rgywm__6c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6 2.5l1.5 8l10 11m-13-11h15m-3 0l-10 11");
}

</style>
