<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yh7tekbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-plus-minus-alt" {...props}></Icon>
<style>
:global(.yh7tekbxv) {
  fill: currentColor;
  d: path("M12 7.998H8v4H6v-4H2v-2h4v-4h2v4h4zm10 10h-8v-2h8zM18.5 4L4 18.5L5.5 20L20 5.5z");
}

</style>
