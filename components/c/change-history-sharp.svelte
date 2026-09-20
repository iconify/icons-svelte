<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etyl813nq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:change-history-sharp" {...props}></Icon>
<style>
:global(.etyl813nq) {
  fill: currentColor;
  d: path("M3.808 19L12 5.885L20.192 19z");
}

</style>
