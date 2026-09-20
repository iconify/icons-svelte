<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv1xuebqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:open-in-new-sharp" {...props}></Icon>
<style>
:global(.nv1xuebqv) {
  fill: currentColor;
  d: path("M3 21V3h9v2H5v14h14v-7h2v9zm6.7-5.3l-1.4-1.4L17.6 5H14V3h7v7h-2V6.4z");
}

</style>
