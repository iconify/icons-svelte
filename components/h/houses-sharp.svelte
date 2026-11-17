<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lba_6gdid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:houses-sharp" {...props}></Icon>
<style>
:global(.lba_6gdid) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 21h8m-8 0H3v-7.625L8 9l5 4.375zm0-14h.01M17 7h.01M17 11h.01M17 15h.01M9 9.875V3h12v18");
}

</style>
