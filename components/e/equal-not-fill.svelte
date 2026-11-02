<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="na57upbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:equal-not-fill" {...props}></Icon>
<style>
:global(.na57upbcn) {
  fill: currentColor;
  d: path("M15.118 8H18a1 1 0 0 1 0 2h-3.882l-2 4H18a1 1 0 0 1 0 2h-6.882l-1.224 2.447a1 1 0 1 1-1.788-.894L8.882 16H6a1 1 0 0 1 0-2h3.882l2-4H6a1 1 0 0 1 0-2h6.882l1.224-2.447a1 1 0 1 1 1.788.894Z");
}

</style>
