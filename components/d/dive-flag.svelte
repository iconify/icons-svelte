<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwsdy7-7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dive-flag" {...props}></Icon>
<style>
:global(.iwsdy7-7g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.125 4.5h9.75A2.625 2.625 0 0 1 19.5 7.125v5.75a2.625 2.625 0 0 1-2.625 2.625h-9.75A2.625 2.625 0 0 1 4.5 12.875v-5.75A2.625 2.625 0 0 1 7.125 4.5M4.5 4.5l15 11M4.5 3v18");
}

</style>
