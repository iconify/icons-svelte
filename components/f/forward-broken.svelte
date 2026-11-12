<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wotq-3b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:forward-broken" {...props}></Icon>
<style>
:global(.wotq-3b7o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.5 17L19.5 12L14.5 7M19.5 12L13 12M9.5 12C7.83333 12 4.5 13 4.5 17");
}

</style>
