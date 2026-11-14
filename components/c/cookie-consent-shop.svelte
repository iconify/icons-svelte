<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9siwob-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cookie-consent-shop" {...props}></Icon>
<style>
:global(.h9siwob-a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0M9 9h.01M15 11h.01m-4.51 4h.01m4.99 1h.01");
}

</style>
