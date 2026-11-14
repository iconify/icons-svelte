<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shyg5_aiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ethics" {...props}></Icon>
<style>
:global(.shyg5_aiv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4v16.5m-6.5-13h13M8 20.5h8M2.5 14l3-6.5l3 6.5a3 3 0 0 1-6 0m13 0l3-6.5l3 6.5a3 3 0 0 1-6 0");
}

</style>
