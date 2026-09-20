<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xv3y31twc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:pause-outline-sharp" {...props}></Icon>
<style>
:global(.xv3y31twc) {
  fill: currentColor;
  d: path("M13.5 18V6H18v12zM6 18V6h4.5v12zm8.5-1H17V7h-2.5zM7 17h2.5V7H7zM7 7v10zm7.5 0v10z");
}

</style>
