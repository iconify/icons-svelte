<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xu96s00hf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:peshawari-chappal" {...props}></Icon>
<style>
:global(.xu96s00hf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c2.75 0 4.75 2.25 4.75 5.5v9.5a3.5 3.5 0 0 1-3.5 3.5h-2.5a3.5 3.5 0 0 1-3.5-3.5v-9.5c0-3.25 2-5.5 4.75-5.5M5.75 7.5l12.5 5m0-5l-12.5 5m0 4h12.5");
}

</style>
