<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qw9-h93ju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:herbal-capsule" {...props}></Icon>
<style>
:global(.qw9-h93ju) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 12h11.5a3.75 3.75 0 0 1 3.75 3.75a3.75 3.75 0 0 1-3.75 3.75H6.25a3.75 3.75 0 0 1-3.75-3.75A3.75 3.75 0 0 1 6.25 12m10.25 0c-2.5-3-1.5-7.5 4-8.5c1 4.5-1 7.5-4 8.5M12 12v7.5");
}

</style>
