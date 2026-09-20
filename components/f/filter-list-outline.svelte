<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9us6-6wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:filter-list-outline" {...props}></Icon>
<style>
:global(.s9us6-6wa) {
  fill: currentColor;
  d: path("M10.558 17v-1h2.865v1zm-3.75-4.5v-1h10.365v1zM4 8V7h16v1z");
}

</style>
