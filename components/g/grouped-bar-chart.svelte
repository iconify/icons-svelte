<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrrewpbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:grouped-bar-chart" {...props}></Icon>
<style>
:global(.nrrewpbye) {
  fill: currentColor;
  d: path("M5 19V8.712h3V19zm4.385 0v-5.654h3V19zM16 19V5h3v14z");
}

</style>
