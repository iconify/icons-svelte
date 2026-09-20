<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="domfhibts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:download-2" {...props}></Icon>
<style>
:global(.domfhibts) {
  fill: currentColor;
  d: path("M4 22v-2h16v2zm8-4L5 9h4V2h6v7h4z");
}

</style>
