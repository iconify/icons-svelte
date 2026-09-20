<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pznt0ob-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:flex-no-wrap" {...props}></Icon>
<style>
:global(.pznt0ob-e) {
  fill: currentColor;
  d: path("M1 17V7h6v10zm8 0V7h6v10zm8 0V7h6v10zM3 15h2V9H3zm16 0h2V9h-2z");
}

</style>
