<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksr1qfbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:plan-30-60-90" {...props}></Icon>
<style>
:global(.ksr1qfbyl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21v-4h6.25v-4H15V9h6.5v12ZM18.25 9V2.5m0 0h3.25l-1 1.75l1 1.75h-3.25Z");
}

</style>
