<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mhc7c_bym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:rakuten-ai" {...props}></Icon>
<style>
:global(.mhc7c_bym) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.5 25.5l-17 6.921V25.5zm-37-3l17-6.921V22.5zm17 20l-6.921-17H22.5zm3-37l6.921 17H25.5z");
}

</style>
