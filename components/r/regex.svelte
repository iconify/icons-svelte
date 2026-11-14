<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwurqkrxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:regex" {...props}></Icon>
<style>
:global(.jwurqkrxx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3H4v18h3M17 3h3v18h-3M12 7.5v9M8 9.75l8 4.5m-8 0l8-4.5");
}

</style>
