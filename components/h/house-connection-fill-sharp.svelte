<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bk8heccba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-connection-fill-sharp" {...props}></Icon>
<style>
:global(.bk8heccba) {
  fill: currentColor;
  d: path("m12.659 2.247l6.222 5.445a1 1 0 0 1 .341.752V17a1 1 0 0 1-1 1H13v2h7a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2h7v-2H5.778a1 1 0 0 1-1-1V8.444a1 1 0 0 1 .341-.752l6.222-5.445c.378-.329.94-.329 1.318 0");
}

</style>
