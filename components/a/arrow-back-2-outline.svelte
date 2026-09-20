<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5hlx-bla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:arrow-back-2-outline" {...props}></Icon>
<style>
:global(.k5hlx-bla) {
  fill: currentColor;
  d: path("M16 19L5 12l11-7zm-2-3.65v-6.7L8.75 12z");
}

</style>
