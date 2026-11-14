<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xp-oubbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:debit-credit-balance" {...props}></Icon>
<style>
:global(.xp-oubbfy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7h18m-3.5-3.5L21 7l-3.5 3.5M21 17H3m3.5-3.5L3 17l3.5 3.5");
}

</style>
