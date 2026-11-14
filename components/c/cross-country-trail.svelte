<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzjf-0b7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cross-country-trail" {...props}></Icon>
<style>
:global(.fzjf-0b7y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21.5C9 15 7 8 10.5 2.5m7.5 19c.5-6.5-6-12.5-4.5-19");
}

</style>
