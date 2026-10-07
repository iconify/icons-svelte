<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uw1s7f9mw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:log-in-sharp-fill" {...props}></Icon>
<style>
:global(.uw1s7f9mw) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 4L21 4L21 20L14 20M13.6493 12L2 12M7.7469 6.204L13.8907 12L7.7469 17.796");
}

</style>
