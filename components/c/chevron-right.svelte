<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvl8vab5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:chevron-right" {...props}></Icon>
<style>
:global(.nvl8vab5v) {
  fill: currentColor;
  d: path("M12.6 12L8 7.4L9.4 6l6 6l-6 6L8 16.6z");
}

</style>
