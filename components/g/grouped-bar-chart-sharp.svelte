<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ji-ln4lds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:grouped-bar-chart-sharp" {...props}></Icon>
<style>
:global(.ji-ln4lds) {
  fill: currentColor;
  d: path("M4 20V8h4v12zm5 0v-7h4v7zm7 0V4h4v16z");
}

</style>
