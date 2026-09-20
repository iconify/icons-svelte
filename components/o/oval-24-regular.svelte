<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjyfqsbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:oval-24-regular" {...props}></Icon>
<style>
:global(.mjyfqsbbl) {
  fill: currentColor;
  d: path("M2 12a8 8 0 0 1 8-8h4a8 8 0 1 1 0 16h-4a8 8 0 0 1-8-8m8-6.5a6.5 6.5 0 0 0 0 13h4a6.5 6.5 0 1 0 0-13z");
}

</style>
