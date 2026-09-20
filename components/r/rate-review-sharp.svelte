<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwr7t9bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:rate-review-sharp" {...props}></Icon>
<style>
:global(.kwr7t9bcw) {
  fill: currentColor;
  d: path("M6 14h3.075L15.1 7.95l-3-3.075l-6.1 6.05zm6.05-5.1l-.95-.925l.975-.975l.925.95zM11.2 14H18v-2h-4.8zM2 22V2h20v16H6z");
}

</style>
