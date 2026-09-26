<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="getdngoom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:record-sharp-fill" {...props}></Icon>
<style>
:global(.getdngoom) {
  fill: currentColor;
  d: path("M21 12C21 16.8325 16.8325 21 12 21C7.1675 21 3 16.8325 3 12C3 7.1675 7.1675 3 12 3C16.8325 3 21 7.1675 21 12Z");
}

</style>
