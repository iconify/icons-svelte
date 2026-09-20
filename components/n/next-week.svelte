<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="db_npacvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:next-week" {...props}></Icon>
<style>
:global(.db_npacvr) {
  fill: currentColor;
  d: path("M2 21V6h6V2h8v4h6v15zm8-15h4V4h-4zm1 11.5l4-4l-4-4l-1.4 1.4l2.6 2.6l-2.6 2.6z");
}

</style>
