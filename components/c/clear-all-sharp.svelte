<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnre-0bwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:clear-all-sharp" {...props}></Icon>
<style>
:global(.xnre-0bwl) {
  fill: currentColor;
  d: path("M4 15.885v-1h12.25v1zM5.866 12.5v-1h12.25v1zM7.75 9.116v-1H20v1z");
}

</style>
