<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6i6d3boh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:layers-2-horizontal-sharp" {...props}></Icon>
<style>
:global(.p6i6d3boh) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 10.182L7.5 2L2 12L7.5 22L12 13.818M22 12L16.5 22L11 12L16.5 2L22 12Z");
}

</style>
