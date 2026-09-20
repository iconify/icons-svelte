<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vejcv_bkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-forward-48-filled" {...props}></Icon>
<style>
:global(.vejcv_bkv) {
  fill: currentColor;
  d: path("M30.44 10.56a1.5 1.5 0 0 1 2.12-2.12l11 11a1.5 1.5 0 0 1 0 2.12l-11 11a1.5 1.5 0 0 1-2.12-2.12L38.878 22H23.5C14.387 22 7 29.387 7 38.5a1.5 1.5 0 0 1-3 0C4 27.73 12.73 19 23.5 19h15.379z");
}

</style>
