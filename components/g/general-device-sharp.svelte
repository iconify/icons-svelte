<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qw1_j2b3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:general-device-sharp" {...props}></Icon>
<style>
:global(.qw1_j2b3t) {
  fill: currentColor;
  d: path("M8 18V3h8v15zm0 3v-2h8v2z");
}

</style>
