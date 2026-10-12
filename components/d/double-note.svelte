<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fr87xtm6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:double-note" {...props}></Icon>
<style>
:global(.fr87xtm6a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.9 19.86a2.5 1.8-20 1 0 4.7-1.71a2.5 1.8-20 1 0-4.7 1.71m6.75-1.25a2.5 1.8-20 1 0 4.7-1.71a2.5 1.8-20 1 0-4.7 1.71m6.75-1.25a2.5 1.8-20 1 0 4.7-1.71a2.5 1.8-20 1 0-4.7 1.71m-8.8.79V6m6.75 10.9V4.88m6.75 10.77V3.75M7.6 6l13.5-2.25");
}

</style>
