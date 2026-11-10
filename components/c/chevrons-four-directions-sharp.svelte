<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iduyabbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chevrons-four-directions-sharp" {...props}></Icon>
<style>
:global(.iduyabbvm) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.589 15.81L2 12L5.589 8.19M8.185 18.41L12 22L15.815 18.41M15.815 5.59L12 2L8.185 5.59M18.411 15.81L22 12L18.411 8.19");
}

</style>
