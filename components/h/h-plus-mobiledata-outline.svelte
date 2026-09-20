<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ty9a486eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:h-plus-mobiledata-outline" {...props}></Icon>
<style>
:global(.ty9a486eq) {
  fill: currentColor;
  d: path("M4 17V7h2v4h6V7h2v10h-2v-4H6v4zm14-2v-2h-2v-2h2V9h2v2h2v2h-2v2z");
}

</style>
