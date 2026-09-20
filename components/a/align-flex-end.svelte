<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmmso4q5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:align-flex-end" {...props}></Icon>
<style>
:global(.nmmso4q5h) {
  fill: currentColor;
  d: path("M2 22v-2h20v2zm8.5-4V4h3v14z");
}

</style>
