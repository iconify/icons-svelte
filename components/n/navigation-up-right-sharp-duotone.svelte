<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkyfw15ez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:navigation-up-right-sharp-duotone" {...props}></Icon>
<style>
:global(.pkyfw15ez) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.997 4L4 9.48L10.725 13.25L14.515 20L19.997 4Z");
}

</style>
