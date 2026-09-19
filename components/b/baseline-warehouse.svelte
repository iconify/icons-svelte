<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="een0ff3rj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-warehouse" {...props}></Icon>
<style>
:global(.een0ff3rj) {
  fill: currentColor;
  d: path("M22 21V7L12 3L2 7v14h5v-9h10v9zm-11-2H9v2h2zm2-3h-2v2h2zm2 3h-2v2h2z");
}

</style>
