<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jujkj_ygm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:jamboard-kiosk-outline-sharp" {...props}></Icon>
<style>
:global(.jujkj_ygm) {
  fill: currentColor;
  d: path("M7 20v-1h4.5v-3H3V4h18v12h-8.5v3H17v1zm-3-5h16V5H4zm0 0V5z");
}

</style>
