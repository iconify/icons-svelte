<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p565k4bfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:format-align-center-sharp" {...props}></Icon>
<style>
:global(.p565k4bfg) {
  fill: currentColor;
  d: path("M4 20v-1h16v1zm4-3.75v-1h8v1zM4 12.5v-1h16v1zm4-3.75v-1h8v1zM4 5V4h16v1z");
}

</style>
