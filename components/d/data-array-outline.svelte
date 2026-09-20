<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyt7kp80q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:data-array-outline" {...props}></Icon>
<style>
:global(.gyt7kp80q) {
  fill: currentColor;
  d: path("M15.423 19v-1H18V6h-2.577V5H19v14zM5 19V5h3.577v1H6v12h2.577v1z");
}

</style>
