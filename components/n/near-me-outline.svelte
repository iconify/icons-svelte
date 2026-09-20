<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shtex93ov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:near-me-outline" {...props}></Icon>
<style>
:global(.shtex93ov) {
  fill: currentColor;
  d: path("m13.13 19.346l-2.426-6.088l-6.089-2.466l-.038-.63l14.846-5.624l-5.661 14.808zm.305-1.969l4.28-11.13l-11.169 4.242l4.9 1.988zm-1.989-4.9");
}

</style>
