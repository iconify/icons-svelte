<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru89se56p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:capital-column" {...props}></Icon>
<style>
:global(.ru89se56p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 4.5h12m-15 3a3 3 0 1 0 6 0a3 3 0 1 0-6 0m12 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-6 0v13h6v-13m-9 0h.01M18 7.5h.01");
}

</style>
