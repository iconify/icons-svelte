<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lr6rb7b-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:artist-profile-heart" {...props}></Icon>
<style>
:global(.lr6rb7b-s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 7a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m-3 13.5c0-3.75 3.25-6 7.5-6q.588 0 1.148.057M18 21.5l-3.25-3.25a2.25 2.25 0 0 1 3.25-3a2.25 2.25 0 0 1 3.25 3Z");
}

</style>
