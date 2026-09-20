<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ptupyt4ab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:on-hub-device-outline-sharp" {...props}></Icon>
<style>
:global(.ptupyt4ab) {
  fill: currentColor;
  d: path("M8.923 19.77v-1h6.154v1zm0-2.77L7.902 4h8.196l-1.021 13zm.927-1h4.3l.87-11H8.98zm0-11h-.87h6.04z");
}

</style>
