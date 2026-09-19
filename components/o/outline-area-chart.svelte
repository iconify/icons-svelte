<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="arohq-6hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-area-chart" {...props}></Icon>
<style>
:global(.arohq-6hv) {
  fill: currentColor;
  d: path("m17 7l-5-4l-5 7l-4-3v13h18V7zm2 9.95l-7-5.45L8 17l-3-2.4V11l2.44 1.83l4.96-6.95L16.3 9H19z");
}

</style>
