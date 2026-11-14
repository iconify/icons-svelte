<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nczuh-73j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:linesman-flag" {...props}></Icon>
<style>
:global(.nczuh-73j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5v19M6.5 3h11A1.5 1.5 0 0 1 19 4.5v7a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 11.5v-7A1.5 1.5 0 0 1 6.5 3M12 3v10M5 8h14");
}

</style>
