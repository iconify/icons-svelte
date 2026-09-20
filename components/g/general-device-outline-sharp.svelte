<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nltnj-wtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:general-device-outline-sharp" {...props}></Icon>
<style>
:global(.nltnj-wtr) {
  fill: currentColor;
  d: path("M8.77 17V4h6.46v13zm1-1h4.46V5H9.77zm-1 3.385v-1h6.46v1zm1-3.385h4.46z");
}

</style>
