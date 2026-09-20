<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzdkpxoyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:listen-outline-bold" {...props}></Icon>
<style>
:global(.zzdkpxoyy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
  d: path("M8 21v-4c-2 -1 -3 -4 -3 -7a6 6 0 0 1 12 0c0 2 -2 3 -3 3s-2 -1 -2 -2");
}

</style>
