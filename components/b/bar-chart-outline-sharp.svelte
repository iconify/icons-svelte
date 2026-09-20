<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjcdftdyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:bar-chart-outline-sharp" {...props}></Icon>
<style>
:global(.bjcdftdyi) {
  fill: currentColor;
  d: path("M16 20v-7h4v7zm-6 0V4h4v16zm-6 0V9h4v11z");
}

</style>
