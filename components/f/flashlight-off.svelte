<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhm1i2bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:flashlight-off" {...props}></Icon>
<style>
:global(.yhm1i2bio) {
  fill: currentColor;
  d: path("M8.48 21V10.416L2.305 4.239l.708-.708l17.284 17.284l-.707.708l-5.108-5.108V21zm-2-16.85V3h10v2.5H7.83zm8 8L8.83 6.5h7.65v1.192l-2 3z");
}

</style>
