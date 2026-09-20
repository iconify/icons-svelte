<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_w9du6kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:check-indeterminate-small-outline" {...props}></Icon>
<style>
:global(.v_w9du6kn) {
  fill: currentColor;
  d: path("M6 13v-2h12v2z");
}

</style>
