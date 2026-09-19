<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edwwstb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:gavel" {...props}></Icon>
<style>
:global(.edwwstb9c) {
  fill: currentColor;
  d: path("m5.25 8.069l2.83-2.827l14.134 14.15l-2.83 2.827zm4.236-4.242L12.314.998l5.657 5.656l-2.828 2.83zM.999 12.315l2.828-2.829l5.657 5.657l-2.828 2.828zM1 21h12v2H1z");
}

</style>
