<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijdxe0fug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-dehaze" {...props}></Icon>
<style>
:global(.ijdxe0fug) {
  fill: currentColor;
  d: path("M2 15.5v2h20v-2zm0-5v2h20v-2zm0-5v2h20v-2z");
}

</style>
