<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bw3rlgxxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:road" {...props}></Icon>
<style>
:global(.bw3rlgxxt) {
  fill: currentColor;
  d: path("M5 19V5h1v14zm6.5 0v-3.077h1V19zm6.5 0V5h1v14zm-6.5-5.462v-3.076h1v3.077zm0-5.461V5h1v3.077z");
}

</style>
