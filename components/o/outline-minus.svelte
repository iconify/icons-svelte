<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="doplcl7zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-minus" {...props}></Icon>
<style>
:global(.doplcl7zi) {
  fill: currentColor;
  d: path("M19 12.998H5v-2h14z");
}

</style>
