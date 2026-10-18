<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ur_xggbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:ban-square-flip-sharp-fill" {...props}></Icon>
<style>
:global(.ur_xggbwn) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21 2L3 2C2.4477 2 2 2.4477 2 3L2 21C2 21.5523 2.4477 22 3 22L21 22C21.5523 22 22 21.5523 22 21L22 3C22 2.4477 21.5523 2 21 2ZM18.5858 4L20 5.4142L5.4142 20L4 18.5858L18.5858 4Z");
}

</style>
