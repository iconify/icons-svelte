<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogb3bzttz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ellipse-bold" {...props}></Icon>
<style>
:global(.ogb3bzttz) {
  fill: currentColor;
  d: path("M12 19C17.5228 19 22 15.866 22 12C22 8.13401 17.5228 5 12 5C6.47715 5 2 8.13401 2 12C2 15.866 6.47715 19 12 19Z");
}

</style>
