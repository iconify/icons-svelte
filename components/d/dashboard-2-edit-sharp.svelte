<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlbhqbc_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:dashboard-2-edit-sharp" {...props}></Icon>
<style>
:global(.mlbhqbc_x) {
  fill: currentColor;
  d: path("M11 11V4h11v7zm-9 9v-7h10v7zm0-9V4h7v7zm12 11v-3.075l6.575-6.55l3.075 3.05L17.075 22zm6.575-5.6l.925-.975l-.925-.925l-.95.95z");
}

</style>
