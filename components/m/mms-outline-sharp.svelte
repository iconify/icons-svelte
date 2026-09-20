<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ot_jerb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:mms-outline-sharp" {...props}></Icon>
<style>
:global(.ot_jerb4p) {
  fill: currentColor;
  d: path("M6 14h12l-3.75-5l-3 4L9 10zm-4 8V2h20v16H6zm3.15-6H20V4H4v13.125zM4 16V4z");
}

</style>
