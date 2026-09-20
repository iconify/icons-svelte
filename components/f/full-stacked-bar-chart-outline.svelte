<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhw73dukv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:full-stacked-bar-chart-outline" {...props}></Icon>
<style>
:global(.fhw73dukv) {
  fill: currentColor;
  d: path("M4 20v-3h4v3zm0-4v-4h4v4zm0-5V4h4v7zm6 9v-7h4v7zm0-8V8h4v4zm0-5V4h4v3zm6 13v-2h4v2zm0-3v-4h4v4zm0-5V4h4v8z");
}

</style>
