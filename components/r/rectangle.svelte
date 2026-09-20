<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ak8laogjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:rectangle" {...props}></Icon>
<style>
:global(.ak8laogjk) {
  fill: currentColor;
  d: path("M3 19V5h18v14z");
}

</style>
