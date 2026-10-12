<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-ob62bld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:arrow-arc-down" {...props}></Icon>
<style>
:global(.v-ob62bld) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4.25v15.5M6.25 14L12 19.75L17.75 14");
}

</style>
