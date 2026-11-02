<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thl1oxbsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:briefcase-fill" {...props}></Icon>
<style>
:global(.thl1oxbsx) {
  fill: currentColor;
  d: path("M7.099 7a5.003 5.003 0 0 1 9.802 0H19a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-8a3 3 0 0 1 3-3ZM9.17 7h5.66a3.002 3.002 0 0 0-5.66 0");
}

</style>
