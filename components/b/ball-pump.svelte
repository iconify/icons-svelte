<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8_r5bbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ball-pump" {...props}></Icon>
<style>
:global(.f8_r5bbaz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 8h2.5A1.75 1.75 0 0 1 15 9.75v9a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 9 18.75v-9A1.75 1.75 0 0 1 10.75 8M6.5 3h11M12 3v5M5.5 20.5h13M15 17c4.5 0 5.5-3 5.5-8");
}

</style>
