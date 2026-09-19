<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1fnx2bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-signal-cellular-alt" {...props}></Icon>
<style>
:global(.p1fnx2bzc) {
  fill: currentColor;
  d: path("M17 4h3v16h-3zM5 14h3v6H5zm6-5h3v11h-3z");
}

</style>
